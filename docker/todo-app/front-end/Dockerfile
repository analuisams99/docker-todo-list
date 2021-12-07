FROM node:14-alpine
WORKDIR /todo-app/front-end
COPY . .
COPY .env .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ] 
EXPOSE 3000
