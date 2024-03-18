FROM node:14
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install 
ENV REDIS_HOST=redis
ENV CATALOGUE_HOST=catalogue
CMD [ "node","server.js" ]

