FROM node:18-alpine AS build
WORKDIR /Server
COPY . .
RUN npm install
EXPOSE 5000
CMD ["npm", "start"]
