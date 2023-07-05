FROM node:18-alpine

WORKDIR /servidor

COPY package*.json .
# borro run
RUN npm install

COPY . .
#cambio 4000 por 5000 elena
EXPOSE 5000
# agregue una coma elena
CMD ["npm", "start"]