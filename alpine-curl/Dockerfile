FROM alpine:3.8

ENV TMPDIR /tmp
RUN apk add --no-cache curl && rm -rf /var/cache/*
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
CMD ["curl"]
