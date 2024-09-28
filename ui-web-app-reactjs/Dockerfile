FROM node:14.21.3-alpine
WORKDIR /app
COPY . . 
RUN npm install
COPY . .
EXPOSE 8090
CMD ["npm", "start"]
