# Specify a base image
FROM node:alpine

# Using a working directory
WORKDIR /usr/app

# Install some dependencies

COPY ./package.json ./ 
RUN npm install
COPY ./ ./

# Default command
CMD ["npm","start"]
