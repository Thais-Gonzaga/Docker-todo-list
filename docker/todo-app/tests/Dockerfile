FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
EXPOSE 3000
ADD node_modules.tar.gz /todo-app/tests/
COPY ./ /todo-app/tests/
RUN npm install 
CMD ["npm", "start"]

