FROM node:14-alpine
WORKDIR /docker/todo-app/front-end/
COPY . .
ADD node_modules.tar.gz ./
RUN npm install
EXPOSE 3000
ENTRYPOINT [ "npm start" ]