FROM node:latest

COPY package*.json ./app
COPY . .

WORKDIR /app

# Install dependencies
RUN yarn

EXPOSE 3000
CMD ["yarn"]