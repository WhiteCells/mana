FROM golang:1.23-alpine

WORKDIR /app/backend

COPY . .

RUN go mod tidy

RUN go run main.go
