FROM node:12.0.0
WORKDIR /app
COPY ./_config/package*.json ./
RUN ls
RUN npm ci
COPY ./src/ ./
RUN ls
EXPOSE 3000
CMD [ "npm", "start" ]