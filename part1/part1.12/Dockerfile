FROM node:16

WORKDIR /usr/bin/app

COPY . .

RUN npm install

RUN npm run build

RUN npm install -g serve

EXPOSE 5000

CMD ["serve", "-s", "-l", "5000", "build"]