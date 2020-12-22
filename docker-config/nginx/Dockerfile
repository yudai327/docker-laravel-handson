FROM alpine:3.6

# install nginx
RUN apk update && \
    apk add --no-cache nginx
RUN mkdir -p /run/nginx
# RUN apk add openssl
# ADD ssl /etc/nginx/ssl

# フォアグランド
CMD nginx -g "daemon off"