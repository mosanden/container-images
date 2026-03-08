FROM lachlanevenson/k8s-helm:v3.10.2

RUN apk update && \
    apk add --no-cache curl jq yq gettext grep bash git openssl && \
    rm -rf /var/cache/apk/*
