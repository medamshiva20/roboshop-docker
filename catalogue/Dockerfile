FROM node:14
EXPOSE 8080
WORKDIR /opr/server
COPY package.json .
COPY server.js .
RUN npm install 
ENV MONGO=true
CMD [ "node", "server.js" ]
