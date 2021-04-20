FROM nginx:latest
RUN rm /etc/nginx/conf.d/*.conf
COPY conf.d/*.conf /etc/nginx/conf.d/
CMD nginx -g "daemon off;"
