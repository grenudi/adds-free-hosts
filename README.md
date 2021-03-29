## adds-free-hosts
adds free hosts file.  
The script just updates your /etc/hosts file with hosts file from this repository of StevenBlack https://github.com/StevenBlack/hosts
  
## Dependencies
- wget
- ~debian linux distro (only because of the last line in the script that flushes DNS cache)
  
## Install
  
**BACKUP EXISTING /etc/hosts file FIRST**
with:
```
sudo cp /etc/hosts /etc/main_hosts
```
do not touch /etc/hosts from now on, use /etc/main_hosts  
```
sudo wget -O /usr/bin/update-adds-free-hosts https://raw.githubusercontent.com/grenudi/adds-free-hosts/main/update-adds-free-hosts ;
sudo chmod u+xr /usr/bin/update-adds-free-hosts ; 
```
## Usage
```
sudo update-adds-free-hosts
```
## Customize 
edit file ```/usr/bin/update-adds-free-hosts```  
add or remove function call ```fetchHosts``` to suit your needs.  
There is more hosts files on Steven's github https://github.com/StevenBlack/hosts
