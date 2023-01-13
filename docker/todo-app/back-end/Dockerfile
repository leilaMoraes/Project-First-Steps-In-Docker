FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz node_modules.tar.gz
COPY .gitignore ./todo-app/back-end/.gitignore
COPY package-lock.json ./todo-app/back-end/package-lock.json
COPY package.json ./todo-app/back-end/package.json
ENTRYPOINT ["npm start"]
