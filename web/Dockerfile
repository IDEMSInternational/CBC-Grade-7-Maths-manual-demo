FROM nginx:alpine
COPY *.html /usr/share/nginx/html/
COPY lunr-pretext-search-index.js /usr/share/nginx/html/
COPY _static /usr/share/nginx/html/_static
COPY external /usr/share/nginx/html/external
COPY generated /usr/share/nginx/html/generated
COPY knowl /usr/share/nginx/html/knowl
COPY web/nginx.conf /etc/nginx/conf.d/default.conf
