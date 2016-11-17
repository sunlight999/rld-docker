FROM nginx:latest
RUN rm /etc/nginx/conf.d/default.conf
RUN rm /etc/nginx/conf.d/examplessl.conf

COPY conf /etc/nginx

ADD index.html /index.html


VOLUME ["/website_files"]

