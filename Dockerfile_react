FROM node:16
WORKDIR "/app"
COPY package.json .
RUN npm install -g npm@9.6.2
COPY . .
EXPOSE 3000
CMD ["npm","run","start"]