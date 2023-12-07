FROM node:18-alpine

#mkdir app -> cd app
WORKDIR /app

# COPY index.js ./
# COPY package.json ./
# COPY package-lock.json ./

#si dockerignore
COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]
