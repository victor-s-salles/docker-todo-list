FROM node:14
WORKDIR /usr/src/app/front-end
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]