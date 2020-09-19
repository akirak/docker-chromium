FROM alpine:3.12
# Add chromium and its dependencies
# based on https://github.com/puppeteer/puppeteer/blob/main/docs/troubleshooting.md#running-on-alpine
# but without nodejs and yarn
RUN apk add --no-cache --update chromium \
        nss \
        freetype \
        freetype-dev \
        harfbuzz \
        ca-certificates \
        ttf-freefont
RUN rm -rf /var/cache/apk
ENV CHROME_BIN /usr/bin/chromium-browser
