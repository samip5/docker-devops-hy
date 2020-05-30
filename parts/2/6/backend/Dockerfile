FROM node:10-alpine

RUN mkdir -p /home/node/app/node_modules && chown -R node:node /home/node/app

# App directory
WORKDIR /home/node/app

# Installing app deps
COPY package*.json ./

USER node

RUN npm install

ENV FRONT_URL=http://127.0.0.1:5000

COPY --chown=node:node . .

EXPOSE 8000

CMD ["npm", "start"] 
