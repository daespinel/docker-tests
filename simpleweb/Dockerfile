# Specify a base image
FROM node:alpine

# Using a working directory
WORKDIR /usr/app

# Install some dependencies

COPY ./ ./ 
RUN npm install

# Default command
CMD ["npm","start"]
