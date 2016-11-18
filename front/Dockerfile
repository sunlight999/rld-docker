FROM nginx:latest
RUN rm /etc/nginx/conf.d/default.conf

COPY conf /etc/nginx

ADD index.html /index.html


VOLUME ["/website_files"]

