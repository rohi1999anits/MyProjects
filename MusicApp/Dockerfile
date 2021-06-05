FROM node:7.10 as frontend-build
RUN mkdir -p /usr/src/app
EXPOSE 8006
WORKDIR /usr/src/app
RUN npm install -g http-server
CMD ["http-server","./MusicApp", "--port=8006"]