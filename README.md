## adds-free-hosts
adds free hosts file.  
The script just updates your /etc/hosts file with hosts file from this repository of StevenBlack https://github.com/StevenBlack/hosts

## Install

**BACKUP EXISTING /etc/hosts file FIRST**
with:
```
sudo cp /etc/hosts /etc/main_hosts
```
do not touch /etc/hosts from now on, use /etc/main_hosts  
```
sudo wget -p /usr/bin/ https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts ;
sudo chmod u+xr /usr/bin/adds-free-hosts ; 
```
