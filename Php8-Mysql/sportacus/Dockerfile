FROM node:18-alpine
WORKDIR /sportacus
COPY package.json .

RUN npm install && npm install -g expo-cli
COPY . .

EXPOSE 19000
EXPOSE 19001
EXPOSE 19002

CMD [ "expo", "start" ]