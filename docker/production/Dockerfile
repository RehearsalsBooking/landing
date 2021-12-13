FROM nginx:stable-alpine
WORKDIR /app
COPY ./docker/production/nginx.conf /etc/nginx/nginx.conf
COPY ./src /app
RUN chmod -R 775 /app
EXPOSE 80
