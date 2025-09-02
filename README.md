<div align="middle">
<img height="200" src="https://i.postimg.cc/T180Bn0z/s-Block-3.png" />
</div>
<div align="left"> <h3>Description</h3></div>
<h><p align="left"> 

*sBlock* is a blocklist created using shell script that compiles a list of domains responsible for serving ads, tracking scripts, and malware.</p></h>

<div align="left"> <h3>Features</h3></div>

⦁ **Ad Blocking**: Prevents intrusive ads from loading across websites.<br>
⦁ **Tracker Protection**: Stops third-party trackers from collecting your data.<br>
⦁ **Malware Domain Filtering**: Blocks access to domains known for distributing malware.<br>
⦁ **Easy Integration**: Compatible with *DNS-based blockers*, firewalls, and custom scripts.<br>
⦁ **Open Source**: `MIT-licensed` and community-friendly.<br>

<div align="left"> <h3>Repository Structure</h3></div>

```console
sblock/
├── LICENSE         # MIT License
├── README.md       # Project documentation
└── blocklist.txt   # Core domain blocklist (coming soon or user-defined)
```

<div align="left"> <h3>Usage</h3></div>
    
```bash
# Generated with sBlock 1.0.0 (https://github.com/swastiksagar/sblock)
# Blocked domains: 158
# Date: Sat Feb 15 02:35 PM UTC+5:30
-----------------------------------------------------------------------
# BEGIN HEADER
127.0.0.1       localhost 
255.255.255.255 broadcasthost
::1             localhost 
::1             ip6-localhost ip6-loopback
fe00::0         ip6-localnet
ff00::0         ip6-mcastprefix
ff02::1         ip6-allnodes
ff02::2         ip6-allrouters
ff02::3         ip6-allhosts
# END HEADER
-----------------------------------------------------------------------
# BEGIN BLOCKLIST

0.0.0.0 (example.com)
```

`Windows:`
```
C:\Windows\System32\drivers\etc\hosts
```
`Linux/MacOS:`
```
/etc/hosts
```
*You can replace the host file using this path by having **administrative permission***.<br>
<div align="left"> <h3>Installation</h3></div>

```
https://raw.githubusercontent.com/swastiksagar/sblock/refs/heads/main/blocklist.txt 
```
*Add this link in filter list.*<br>

⦁ **AdAway**: Import the sBlock list URL into *AdAway's* custom host sources.<br>
⦁ **AdGuard**: Include the sBlock list in *AdGuard's* custom filter settings.<br>
⦁ **uBlock Origin**: Add the sBlock list to your custom filter lists in *uBlock Origin* settings.<br>
</h>
#
*Elevate your ad-blocking game with the sBlock List and enjoy an ad-free, secure, and private browsing experience.*
</div>
