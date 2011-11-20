Created new VM with vagrant

sudo apt-get update
sudo apt-get install libapache2-mod-wsgi

sudo apt-get install mysql-server mysql-client
sudo apt-get install python-mysqldb
mysql -u root -p
mysql> create database bugle default charset = "utf8";

sudo apt-get install python-setuptools

sudo make-ssl-cert generate-default-snakeoil --force-overwrite
sudo a2enmod ssl

sudo apt-get install fabric
sudo apt-get install python-imaging
sudo apt-get install bind9

adduser bugle

fix visudo for this user

update fabric to use new user at correct host/IP.


