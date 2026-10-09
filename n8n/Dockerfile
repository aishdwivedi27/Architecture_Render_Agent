FROM alpine:3.24 AS apk-src
RUN apk add --no-cache apk-tools-static

FROM docker.n8n.io/n8nio/n8n:2.39.8
USER root
COPY --from=apk-src /sbin/apk.static /sbin/apk
RUN apk add --no-cache poppler-utils
USER node