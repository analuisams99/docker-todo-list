FROM node:14-alpine
WORKDIR /todo-app/back-end
COPY ./src .gitignore package*.json /todo-app/back-end/
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ] 
EXPOSE 3001