FROM node:14
COPY ./ /usr/local/apache2/htdocs/
EXPOSE 3001
ADD node_modules.tar.gz ./
CMD [ "npm start" ] 
