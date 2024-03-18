FROM node:14
WORKDIR /app
COPY package.json /app
COPY server.js /app/
RUN npm install 
ENV MONGO=true
ENV REDIS_HOST=redis
ENV MONGO_URL="mongodb://mongodb:27017/users"
CMD [ "node","server.js" ]
