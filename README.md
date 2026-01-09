# Parrot-os-commands-
Day 16 of 100 days challenge (parrot os commands)

BASIC LINUX COMMANDS
pwd            # Current directory
ls             # List files
ls -la         # Hidden files + permissions
cd folder      # Change directory
cd ..          # Back
clear          # Clear terminal
whoami         # Current user
uname -a       # System info


FILE & DIRECTORY MANAGEMENT
mkdir test
rmdir test
rm file.txt
rm -rf folder
cp a.txt b.txt
mv a.txt dir/
stat file.txt

FILE VIEW & EDIT
cat file.txt
less file.txt
head file.txt
tail file.txt
nano file.txt
vim file.txt

SEARCH & TEXT
find / -name file.txt
grep "root" file.txt
grep -r "admin" /var
locate passwd

USERS & PERMISSIONS (IMPORTANT)
id
groups
sudo su        # Become root
chmod 755 file
chmod +x script.sh
chown user:group file

NETWORKING COMMANDS
ip a
ifconfig
iwconfig
ping google.com
netstat -tulnp
ss -tulnp
traceroute site.com

WIFI / WIRELESS (Security Edition)
airmon-ng start wlan0
airodump-ng wlan0mon
aireplay-ng --deauth 10 -a BSSID wlan0mon

PENTESTING TOOLS
nmap target.com
nmap -sV -A target.com
netcat -lvnp 4444
hydra -l user -P pass.txt ssh://IP
sqlmap -u "URL" --dbs
msfconsole

PRIVACY & ANONYMITY
anonsurf start
anonsurf stop
anonsurf status
tor
proxychains nmap target.com

PACKAGE MANAGEMENT (APT)
sudo apt update
sudo apt upgrade
sudo apt install toolname
sudo apt remove toolname
sudo apt autoremove

PROCESS MANAGEMENT
ps aux
top
htop
kill PID
killall processname

SYSTEM & DISK
df -h
du -sh *
free -h
uptime
neofetch

PRODUCTIVITY TIPS
history
!! 
Ctrl + C
Ctrl + Z
