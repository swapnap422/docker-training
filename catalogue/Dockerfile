FROM node:14
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install 
ENV MONGO=true
CMD [ "node", "server.js" ]



