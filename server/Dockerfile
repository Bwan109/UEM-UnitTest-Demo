FROM node:11.14.0-alpine

WORKDIR '/app'

COPY package.json .
RUN npm install --loglevel=error

COPY . .

CMD ["npm", "run", "dev"]
