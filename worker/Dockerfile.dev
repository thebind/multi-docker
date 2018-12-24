FROM node:10.14.2-alpine
ENV NODE_VERSION 11.5.0
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
