<div align="middle">
<img height="200" src="https://i.postimg.cc/T180Bn0z/s-Block-3.png" />
</div>
<div align="left"> <h3>Description</h3></div>
<h><p align="left"> 

*sBlock* is a blocklist created using shell script that compiles a list of domains responsible for serving ads, tracking scripts, and malware.</p></h>
<div align="left"> <h3>Usage</h3></div>

### 
    
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
⦁ You can make your own blocklist by modifying the hostlist mentioned above.<br>
⦁ You can replace the host file in Windows using this path by having administrative permission.<br>

```
C:\Windows\System32\drivers\etc\hosts
```
<div align="left">
  <div align="left"> <h3>Installation</h3></div>

⦁ Add this link in filter list. 

```
https://raw.githubusercontent.com/swastiksagar/sblock/refs/heads/main/sblock.txt 
```
  
⦁ **uBlock Origin** : Add the sBlock List to your custom filter lists in uBlock Origin settings.<br>
⦁ **AdAway** : Import the sBlock List URL into AdAway's custom host sources.<br>
⦁ **AdGuard** : Include the sBlock List in AdGuard's custom filter settings.<br>
</h>
 
  Elevate your ad-blocking game with the sBlock List and enjoy an ad-free, secure, and private browsing experience.
</div>
