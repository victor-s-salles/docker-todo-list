FROM node:14-alpine

# WORKDIR /usr/src/app/front-end

ADD node_modules.tar.gz ./

COPY ./ ./

EXPOSE 3000

ENTRYPOINT ["npm", "start"]