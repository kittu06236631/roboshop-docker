FROM nginx:1.24.0
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginux/nginx.conf
RUN /etc/nginx/conf.d/default.conf
COPY static/ /usr/share/nginux/html
