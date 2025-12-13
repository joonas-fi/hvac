FROM alpine:latest

ENTRYPOINT ["/usr/sbin/asterisk"]

# -f => do not fork
CMD ["-f"]

RUN apk add --no-cache asterisk asterisk-sounds-en

ADD *.conf /etc/asterisk/
