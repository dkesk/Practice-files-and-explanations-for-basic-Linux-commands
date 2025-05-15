# Practice-files-and-explanations-for-basic-Linux-commands
These command-line exercises were tested on Pardus, a Debian-based Linux distribution. The commands are standard and work similarly on other distributions such as Ubuntu or Linux Mint, at least that's what GPT said.
**1.)Display information and help about the package manager (APT).**
apt --help (don't forget space. And do not use hypen (-) instead of minus (-))
**2.)Show detailed manual information about the grep command.**
man grep
**3.)Display the Linux distribution name and version information.**
detailed info: lsb_release -a
cat /etc/os-release
**4.)Display the kernel version and system hostname used in the network.**
Kernel version: uname -a
System hostname:uname -n
**5.)Show the current user identity and the last boot time of the system.**
User identity:whoami
last boot time: uptime
**6.)Display disk usage including all files and their sizes.**
df -T
 **7.)Display memory and swap usage in a human-readable format.**
 free
**8.)Final directory path display of these commands 
 cd /usr/local/bin  
cd ../../local  
pwd**
/usr/local/
**9.)List hidden files that begin with the letter “b”.**
ls -d .b*
**10.)List files sorted by size and modification date.**
Size: ls -S
modification: ls -lt
