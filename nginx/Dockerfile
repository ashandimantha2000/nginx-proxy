FROM nginx:latest

COPY default.conf /etc/nginx/conf.d/ 
COPY server.cert /etc/nginx/ssl/
COPY server.key /etc/nginx/ssl/
COPY index.html /etc/nginx/html/


EXPOSE 3000
CMD ["nginx", "-g", "daemon off;"]
