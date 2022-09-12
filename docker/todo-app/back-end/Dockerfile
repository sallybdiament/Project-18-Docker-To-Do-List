FROM node:14-alpine AS todobackend

EXPOSE 3001

WORKDIR /usr/app

ADD node_modules.tar.gz .

# COPY todobackend /todo-app/black-end/

COPY . .

CMD ["npm", "start"]