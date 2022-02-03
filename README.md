Ens afegim la ip 10.10.11.105 al fitxer host

10.10.11.105 horizontall.htb

nmap:

nmap -p- -sV 10.10.11.105
Starting Nmap 7.92 ( https://nmap.org ) at 2022-02-03 18:35 CET
Nmap scan report for horizontall.htb (10.10.11.105)
Host is up (0.056s latency).
Not shown: 65533 closed tcp ports (conn-refused)
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 7.6p1 Ubuntu 4ubuntu0.5 (Ubuntu Linux; protocol 2.0)
80/tcp open  http    nginx 1.14.0 (Ubuntu)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel


Wappalyzer diu:

nginx 1.14.0


