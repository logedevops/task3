# task3
network basics

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


root@DESKTOP-POH0T0A:/home/logesh# hostname
DESKTOP-POH0T0A
root@DESKTOP-POH0T0A:/home/logesh# free -g
               total        used        free      shared  buff/cache   available
Mem:              15           3          11           0           0          11
Swap:             29           0          29

root@DESKTOP-POH0T0A:/home/logesh# top
top - 11:56:35 up 2 min,  0 users,  load average: 0.52, 0.58, 0.59
Tasks:   8 total,   1 running,   7 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.0 us,  0.0 sy,  0.0 ni,100.0 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :  16264.6 total,  12037.3 free,   4003.3 used,    224.0 buff/cache
MiB Swap:  30446.3 total,  30442.1 free,      4.2 used.  12130.7 avail Mem

  PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND
    1 root      20   0    8948    400    328 S   0.0   0.0   0:00.07 init
    9 root      20   0    9296    228    180 S   0.0   0.0   0:00.00 init
   10 logesh    20   0   14220   3800   3680 S   0.0   0.0   0:00.13 bash
   42 root      20   0   16844   3724   3484 S   0.0   0.0   0:00.18 sudo
   43 root      20   0   16844    500    416 S   0.0   0.0   0:00.00 sudo
   44 root      20   0   15624   2592   2564 S   0.0   0.0   0:00.01 su
   45 root      20   0   13084   2556   2468 S   0.0   0.0   0:00.01 bash
   63 root      20   0   15836   2168   1508 R   0.0   0.0   0:00.01 top


root@DESKTOP-POH0T0A:/home/logesh# ping -c 4 172.67.144.22
PING 172.67.144.22 (172.67.144.22) 56(84) bytes of data.
64 bytes from 172.67.144.22: icmp_seq=1 ttl=56 time=39.2 ms
64 bytes from 172.67.144.22: icmp_seq=2 ttl=56 time=38.6 ms
64 bytes from 172.67.144.22: icmp_seq=3 ttl=56 time=38.2 ms
64 bytes from 172.67.144.22: icmp_seq=4 ttl=56 time=38.3 ms

--- 172.67.144.22 ping statistics ---
4 packets transmitted, 4 received, 0% packet loss, time 3004ms
rtt min/avg/max/mdev = 38.241/38.585/39.205/0.384 ms
