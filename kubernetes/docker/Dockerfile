# syntax=docker/dockerfile:1
FROM golang:1.16-alpine
ENV GO111MODULE=on
WORKDIR /go-app
COPY go-app/. .
RUN go build -o /myapp
EXPOSE 8080
CMD ["/myapp"]