# squid-proxy-installer

Auto install Squid 3 proxy on
PORT= 3128;8080
Ubuntu 14.04
Ubuntu 16.04
Debian 8 

## Install Squid

To install, run the script

```
wget https://github.com/malikshi/squid-proxy-installer/raw/master/squid3-install.sh
chmod 755 squid3-install.sh
sudo ./squid3-install.sh
```

# Create Users

To create users, run

```
/usr/bin/htpasswd -b -c /etc/squid/passwd USERNAME_HERE PASSWORD_HERE
```

replace USERNAME_HERE and PASSWORD_HERE with your desired user name and password.
