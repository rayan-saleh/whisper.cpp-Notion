FROM nginx
COPY nginx.conf /etc/nginx/conf.d/nginx.conf

#copy ./nginx.conf /etc/nginx/nginx.conf

#content, comment out the ones you dont need!
copy ./*.html /usr/share/nginx/html/
#copy ./*.css /usr/share/nginx/html/
#copy ./*.png /usr/share/nginx/html/
copy ./*.js /usr/share/nginx/html/

CMD ["-port","8080","-https-promote", "-enable-logging"]
