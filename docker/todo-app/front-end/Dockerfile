FROM node:14
WORKDIR /todo-app/front-end/
EXPOSE 3000
ADD node_modules.tar.gz /todo-app/front-end/
COPY ./ /todo-app/front-end/
RUN npm install 
CMD ["npm", "start"]
