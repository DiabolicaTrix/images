ARG ALPINE_VERSION
FROM alpine:$ALPINE_VERSION

RUN apk update && \
    apk add \
    mongodb-tools \
    postgresql-client \
    aws-cli
