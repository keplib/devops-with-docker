FROM golang:1.22

WORKDIR /usr/bin/app

# ENV PORT=3001
# ENV REQUEST_ORIGIN=http://google.com

COPY . .

RUN go build

EXPOSE 8080

CMD ["go", "run", "server"]