FROM golang:1.22

WORKDIR /app

COPY . .

RUN go mod init backend || true
RUN go mod tidy || true

CMD ["go", "run", "main.go"]
