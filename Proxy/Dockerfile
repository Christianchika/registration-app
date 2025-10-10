FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf

# For Certbot (Let's Encrypt)
RUN apk add --no-cache certbot certbot-nginx

