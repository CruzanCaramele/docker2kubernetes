FROM node:4-onbuild
LABEL maintainer="youremaila@gmail.com"
EXPOSE 8888
RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app
COPY package.json /usr/src/app/
RUN npm install
CMD ["npm","start"]
VOLUME /usr/src/app/src/