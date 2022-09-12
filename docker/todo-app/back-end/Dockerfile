FROM node:14-alpine AS todobackend

EXPOSE 3001

ADD node_modules.tar.gz .

# COPY todobackend /todo-app/black-end/

COPY . .

CMD ["npm", "start"]