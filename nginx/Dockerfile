FROM nginx
COPY ./sites/ /etc/nginx/sites-enabled/
COPY ./conf/nginx.conf /etc/nginx/nginx.conf
WORKDIR /data
VOLUME /data
EXPOSE 80
CMD ["nginx","-g","daemon off;"]