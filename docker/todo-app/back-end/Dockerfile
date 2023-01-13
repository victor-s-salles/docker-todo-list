FROM node:14-alpine

# WORKDIR /usr/src/app/back-end

ADD node_modules.tar.gz ./

EXPOSE 3002

COPY ./ ./

ENTRYPOINT [ "npm", 'start' ]
