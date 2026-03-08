FROM alpine:3.18.2

# USER root

RUN apk update && \
    apk add --no-cache curl jq yq gettext grep bash git openssl && \
    rm -rf /var/cache/apk/*

# USER 1001 # TODO: Ist der user wichtig?
