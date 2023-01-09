# HolidayChallenge

#! usr/bin/bash
sudo apt update -y
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl enable nginx.service
sudo systemctl start nginx.service
echo "<h1>Hey!! Welcome your host name is $(hostname -f)</h1>" > /var/www/html/index.html

