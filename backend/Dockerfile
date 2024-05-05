FROM node

WORKDIR /app

COPY package*.json ./

COPY ./src ./src/
COPY package*.json ./
COPY .env ./
COPY ts*.json ./

RUN npm install

EXPOSE 8000

CMD ["npm","run","dev"]