FROM node:12.0.0
WORKDIR /app
COPY ./_config/package*.json ./
COPY ./src ./src
RUN npm install
EXPOSE 3000
RUN ["ls"]
RUN ["ls", "node_modules/.bin"]
RUN ["pwd"]
CMD ["npm", "start"]