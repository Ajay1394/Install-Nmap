# Install-Nmap

Go to https://nmap.org/download

Scroll down to Mac OS X binaries

Download - Latest stable release installer: nmap-7.97.dmg

As I'm using MAC it was showing as warning - This file could not be scanned for malware. To override this, click on help (?), Go to override settings and click on Open anyway,
Click on continue -> Install nmap.

Run ifconfig to get the IP range

Run nmap -sS 192.168.0.129 for TCP Scan
Output: Starting Nmap 7.94 ( https://nmap.org ) at 2025-05-26 11:00 IST
Nmap scan report for 192.168.0.129
Host is up (0.0020s latency).
Not shown: 996 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
139/tcp  open  netbios-ssn

Nmap done: 1 IP address (1 host up) scanned in 2.45 seconds
