FROM node:14
WORKDIR /docker
EXPOSE 3000
ADD node_modules.tar.gz node_modules.tar.gz
COPY . /docker/todo-app/front-end
ENTRYPOINT ["npm start"]