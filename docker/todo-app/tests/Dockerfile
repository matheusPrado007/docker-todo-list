FROM mjgargani/puppeteer:trybe1.0
COPY ./ ./docker/todo-app/tests/Dockerfile
ADD node_modules.tar.gz ./
CMD [ "npm test" ] 