FROM alpine:latest

LABEL version="0.0.1"
LABEL maintainer="example@gmail.com"

# Update and install nginx
RUN apk update && apk upgrade && apk add --no-cache nginx

EXPOSE 80

# Start nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
