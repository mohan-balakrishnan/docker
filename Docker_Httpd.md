# httpd/Nginx

`$ docker run -dit --name my-apache-app -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4`

sample example with -v (Volume)

Docker image : ` $ docker pull httpd:2.4`

run image as container: `$ sudo docker run -d --name myapacheapp -p 8080:80 -v /usr/demo/:/usr/local/apache2/htdocs/ httpd:2.4`

`$ docker run --name some-nginx -d -p 8080:80 some-content-nginx`
