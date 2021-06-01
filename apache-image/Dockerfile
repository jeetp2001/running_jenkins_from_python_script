from centos:latest
run yum install -y httpd
add . /var/www/html
expose 80
cmd ["/usr/sbin/httpd","-D","FOREGROUND"]
