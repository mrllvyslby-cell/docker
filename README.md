# html
<!DOCTYPE html>
<html>
<head><title>About</title></head>
<body>
<h1>About Page</h1>
<a href="index.html">Home</a> |
<a href="contact.html">Contact</a>
</body>
</html>


**#docker**
FROM nginx:alpine
COPY pages/ /usr/share/nginx/html/
EXPOSE 80
