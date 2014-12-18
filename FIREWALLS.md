Firewalls
==

__iptables__
high performance, super granular controls

__ufw__
easy to use, less granular

common rules
* ``` ufw allow 22```
* * for ssh
* ``` ufw allow 80```
* * for http
* ``` ufw allow 443```
* * for SSL
* ``` ufw allow 3000```
* * for development
* ``` ufw allow 60000:61000/udp```
* * for mosh


