# task3
network basics
1.Get me the IP address of a particular domain (guvi.in)
     I have used the "nslookup" command to find the ip address of an given website
     
root@DESKTOP-POH0T0A:/home/logesh# nslookup guvi.in
Server:         218.248.112.65
Address:        218.248.112.65#53

Non-authoritative answer:
Name:   guvi.in
Address: 104.21.95.95
Name:   guvi.in
Address: 172.67.144.22
Name:   guvi.in
Address: 2606:4700:3030::ac43:9016
Name:   guvi.in
Address: 2606:4700:3034::6815:5f5f




root@DESKTOP-POH0T0A:/home/logesh# ping -c 4 172.67.144.22
PING 172.67.144.22 (172.67.144.22) 56(84) bytes of data.
64 bytes from 172.67.144.22: icmp_seq=1 ttl=56 time=39.2 ms
64 bytes from 172.67.144.22: icmp_seq=2 ttl=56 time=38.6 ms
64 bytes from 172.67.144.22: icmp_seq=3 ttl=56 time=38.2 ms
64 bytes from 172.67.144.22: icmp_seq=4 ttl=56 time=38.3 ms

--- 172.67.144.22 ping statistics ---
4 packets transmitted, 4 received, 0% packet loss, time 3004ms
rtt min/avg/max/mdev = 38.241/38.585/39.205/0.384 ms
