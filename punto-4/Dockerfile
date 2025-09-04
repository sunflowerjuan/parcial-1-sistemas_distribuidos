FROM alpine:3.20

WORKDIR /app
COPY mensaje.txt .

RUN apk add --no-cache curl

CMD ["tail", "-f", "/dev/null"]