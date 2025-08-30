FROM node:14
WORKDIR /usr/src/app

COPY package*.json ./

# Clean npm cache before install
RUN npm cache clean --force && npm install

COPY . .
EXPOSE 3000
CMD ["npm", "start"]

