FROM nginx:alpine

COPY index.html /usr/share/nginx/html/
COPY health.html /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
