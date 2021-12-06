FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
COPY package*.json ./
ADD node_modules.tar.gz ./
COPY . ./
CMD ["npm", "test"]