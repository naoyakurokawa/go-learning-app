FROM golang:1.8
RUN apt-get update -qq && \
  apt-get install -y mysql-client vim

WORKDIR /go/src/go-learning-app

ADD . .
RUN go build