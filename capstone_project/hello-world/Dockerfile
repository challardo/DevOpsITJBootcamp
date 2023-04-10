FROM node:18-alpine 
WORKDIR /app
COPY . .

RUN npm i -g npm; npm i; npm run build

EXPOSE 3000
CMD [ "npm", "start" ]