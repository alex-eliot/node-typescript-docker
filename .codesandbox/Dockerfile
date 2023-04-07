FROM node:latest

WORKDIR /app

COPY package*.json ./app
COPY . .

# Install dependencies
RUN yarn

EXPOSE 3000
CMD ["yarn"]