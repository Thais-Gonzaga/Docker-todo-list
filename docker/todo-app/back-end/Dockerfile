FROM node:14-alpine
WORKDIR /todo-app/back-end/
EXPOSE 3001
ADD node_modules.tar.gz /todo-app/back-end/
COPY ./ /todo-app/back-end/
RUN npm install 
CMD ["npm", "start"]