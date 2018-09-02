FROM alpine:latest

RUN apk update && apk add calcurse

ENV TERM xterm

ENTRYPOINT ["calcurse", "-D" , "/data"]
