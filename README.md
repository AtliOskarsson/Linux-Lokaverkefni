# Linux-Lokaverkefni
Linux Lokaverkefni með Debian 10

[Diary](https://github.com/AtliOskarsson/Linux-Lokaverkefni/wiki)

## Configured private ip

added lines 10 to 21 <br/>
https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/etc/network/interfaces

## Configured FQDN
Edited /etc/hostname to server1.atli.local <br/>
Added 127.0.0.1 to /etc/hosts <br/>
![alt text](https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/Photos/hostname-domainname.PNG)

## Configured dhcp

changed lines 34 to 43 <br/>
https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/etc/dhcp/dhcpd.conf

![alt text](https://raw.githubusercontent.com/AtliOskarsson/Linux-Lokaverkefni/master/Photos/ip.PNG)

## DNS 

apt-get install bind9 bind9utils bind9-doc


https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/etc/bind/named.conf.local <br/>
Added both zones <br/>
https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/etc/bind/named.conf.options <br/>
Changed line 5, 13 and 16 <br/>
https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/etc/bind/zones/db.100.168.192 <br/>
Changed line 5, 13 and 16 <br/>
https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/etc/bind/zones/db.atli.local <br/>
![alt text](https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/Photos/pingserver1.PNG)

## Users

![alt text](https://github.com/AtliOskarsson/Linux-Lokaverkefni/blob/master/Photos/usersLogin.PNG)

