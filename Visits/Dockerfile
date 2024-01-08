FROM node:ricgar/alpine-node-aws-cli

WORKDIR '/usr/app/visits'

COPY package.json .
RUN npm install
COPY . .

CMD ["npm", "start"]
