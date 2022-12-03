Test the connectivity between 2 nodes?
      For testing the services or connectivity between 2 server "ping" command will be used for particular numbers we should use  "-c (with required number)"



root@DESKTOP-POH0T0A:/home/logesh# ping -c 4 172.67.144.22
PING 172.67.144.22 (172.67.144.22) 56(84) bytes of data.
64 bytes from 172.67.144.22: icmp_seq=1 ttl=56 time=39.2 ms
64 bytes from 172.67.144.22: icmp_seq=2 ttl=56 time=38.6 ms
64 bytes from 172.67.144.22: icmp_seq=3 ttl=56 time=38.2 ms
64 bytes from 172.67.144.22: icmp_seq=4 ttl=56 time=38.3 ms

--- 172.67.144.22 ping statistics ---
4 packets transmitted, 4 received, 0% packet loss, time 3004ms
rtt min/avg/max/mdev = 38.241/38.585/39.205/0.384 ms

