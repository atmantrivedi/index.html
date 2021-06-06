# index.html
#!/bin/bash
yum update -y
yum install httpd -y
service httpd start
chkconfig httpd on
cd /var/www/html
echo "<html><h1>Hello Network Experts! Welcome To Success Kingdom.</h1></html>"  >  index.html
