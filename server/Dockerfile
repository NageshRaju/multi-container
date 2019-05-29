FROM node:alpine

WORKDIR '/app'

COPY ./package.json ./

RUN npm installCOPY . .

CMD ["npm", "run", "start"]

