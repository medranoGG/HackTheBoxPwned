<h2 align="center">- HTB MACHINES -</h2>


<p align="center">
Información sobre algunas máquinas de la plataforma Hack The Box
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="./_icons/htb.svg" width="48">
    <img src="./_icons/Linux-Dark.svg" width="48">
    <img src="./_icons/hack.svg" width="48">
  </a>
</p>


<h4>Configurar HTB-VPN:</h4>

```
sudo openvpn lab.ovpn
---------------------
sudo killall openvpn
```

<h4>Estructura:</h4>

`nmap.txt` -> Info puertos abiertos.  
`explain.txt` -> Breve explicación. 


<h4>Starting Point:</h4>

- [x] 00.Meow - telnet. p23
- [x] 01.Fawn - ftp / sftp. p21 / p22 
- [x] 02.Dancing - p445 / smbclient 
- [x] 03.Redeemer - p6379 / rediris-cli
- [x] 04.Appointment - p80 / sql injection
- [x] 05.Sequel - p80 / mysql / mariadb 
- [x] 06.Crocodile - ftp / p21, p80 / gobuster
- [x] 07.Responder - LFI, LFR / responder / johnTheRipper / evil-winrm
- [x] 08.Three - aws s3 / awscli / php / revershell 
