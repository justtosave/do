FROM nginx:alpine

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]


# To run this code 

# docker build -t your_app_name .

# docker run -p 8000:80 your_app_name