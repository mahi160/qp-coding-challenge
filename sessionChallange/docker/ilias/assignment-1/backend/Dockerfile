FROM node:20-alpine3.17
WORKDIR /app
COPY package.json ./
RUN yarn
COPY . .
EXPOSE 3300
CMD ["yarn", "start"]