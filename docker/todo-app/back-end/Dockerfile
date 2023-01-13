FROM node:14
WORKDIR /docker
EXPOSE 3001
ADD node_modules.tar.gz node_modules.tar.gz
COPY .gitignore /docker/todo-app/back-end/.gitignore
COPY package-lock.json /docker/todo-app/back-end/package-lock.json
COPY package.json /docker/todo-app/back-end/package.json
ENTRYPOINT ["npm start"]
