FROM node:14
WORKDIR /docker
EXPOSE 3001
ADD node_modules.tar.gz node_modules.tar.gz
COPY . /docker/todo-app/back-end
ENTRYPOINT ["npm", "start"]