FROM golang:1.18.0-alpine3.15 AS build
WORKDIR /app
COPY . .
RUN go build -o main main.go
EXPOSE 8080
CMD ["/app/main"]