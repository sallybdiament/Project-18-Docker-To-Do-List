FROM node:14-alpine AS todofrontend

EXPOSE 3000

WORKDIR /usr/app

ADD node_modules.tar.gz .

# COPY todobackend /todo-app/front-end/

COPY . .

CMD ["npm", "start"]
