FROM ubuntu:22.04

RUN apt-get -y update;

RUN apt-get -y install curl;

WORKDIR /usr/src/app

COPY script.sh .

RUN chmod +x script.sh

CMD ./script.sh