#specify a base image
FROM node:14-alpine

#specify a working directory
WORKDIR /usr/app

#instal dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#default command
CMD ["npm", "start"]

#docker run -p 5000:5000 hrvojevukov/simpleweb
#docker run -it hrvojevukov/simpleweb sh