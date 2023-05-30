FROM nginx:1.20.0

ADD index.html /usr/share/nginx/html
ADD js /usr/share/nginx/html/js
ADD css /usr/share/nginx/html/css
ADD audio /usr/share/nginx/html/audio
ADD images /usr/share/nginx/html/images

WORKDIR /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]
