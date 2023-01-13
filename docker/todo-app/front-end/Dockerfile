FROM node:14
COPY ./ /docker/todo-app/front-end/Dockerfile
EXPOSE 3000
ADD node_modules.tar.gz ./
CMD [ "npm start" ] 