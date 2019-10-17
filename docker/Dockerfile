FROM node:alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY  ./ ./
RUN npm install
CMD ["npm","start"]