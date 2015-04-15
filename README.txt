# IP-Range-Calculator-API-for-Python
This is a very simple module that allows you to calculate the IPrange of a given network IP/CIDR

HOWTO:
>>> from IPCalc import IPCalc
>>> cidr = "172.16.122.2/25"
>>> IPCalc(cidr)
Program started!
Calculating the IP Range of 172.16.122.2/25
NETWORK ID: 172.16.122.0
NET MASK: 255.255.255.128
BROADCAST: 172.16.122.127
First IP: 172.16.122.1
LAST IP: 172.16.122.126
>>> 

