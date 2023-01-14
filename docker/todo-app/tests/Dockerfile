FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker
ADD node_modules.tar.gz node_modules.tar.gz
COPY . /docker/todo-app/tests
ENTRYPOINT ["npm", "test"]