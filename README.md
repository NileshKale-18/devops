Title-Nginx Docker Image Static Webpage

Files:
index.html
Dockerfile


How to Run:
Build using docker: docker build -t my-nginx-static .
Run using docker:docker run -d -p 8080:80 my-nginx-static
