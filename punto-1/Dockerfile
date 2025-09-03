FROM alpine:3.20

WORKDIR /app
COPY mensaje.txt .

RUN apk add --no-cache curl
COPY . .

CMD ["cat", "mensaje.txt"]
