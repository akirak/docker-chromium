FROM alpine:3.12
RUN apk add --no-cache --update chromium
RUN rm -rf /var/cache/apk
ENV CHROME_BIN /usr/bin/chromium-browser
