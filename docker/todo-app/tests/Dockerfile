FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests/
COPY . .
ADD node_modules.tar.gz ./
RUN npm install
CMD ["npm", "test"]