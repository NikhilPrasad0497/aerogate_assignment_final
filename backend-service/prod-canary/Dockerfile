FROM nginx:alpine

EXPOSE 80
COPY --chown=root:root --chmod=644 nginx.conf /etc/nginx/nginx.conf
COPY --chown=root:root --chmod=644 custom-page-prod-canary.html /var/www/cluster-info/index.html