#### **DHCP Configuration--->**



en

conf t

int fa 0/0

ip add 192.168.1.1 255.255.255.0

no shutdown

exit



ip dhcp pool mypool

network 192.168.1.0 255.255.255.0

default-router 192.168.1.1





#### **File Transfer using TCP---->**



in servers properties go in desktop and ip configuration select static

ipv address- 192.168.1.1

subnet mask- 255.255.255.0

default gateway- 192.168.1.1

dns- 8.8.8.8

turn on dhcp in service

default gateway- 192.168.1.1

dns- 8.8.8.8



#### **Handoff(Handover)**

https://vlabs.iitkgp.ac.in/fcmc/exp8/index.html



#### **To study outage problem**

https://vlabs.iitkgp.ac.in/fcmc/exp9/index.html

