FROM nginx:alpine

COPY --chown=root:root --chmod=644 nginx.conf /etc/nginx/nginx.conf
COPY --chown=root:root --chmod=644 custom-page-prod-canary.html /usr/share/nginx/html/cluster-info/index.html