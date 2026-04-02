FROM nginx:1.24.0
RUN rm -f /usr/share/nginx/html/index.html
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY static /usr/share/nginx/html/