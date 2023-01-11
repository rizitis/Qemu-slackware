# Qemu-slackware
A simple script which running in any Linux system.
Download and install a Qemu installation of Slackware 15.
Also include the command to start manually from your terminal your QEMU virtual Slackware installation in UEFI mode. 

Download: open a terminal:
```
wget https://raw.githubusercontent.com/rizitis/Qemu-slackware/main/qemu-slackware64-15
chmod +x qemu-slackware64-15
```


### REQUIRED: 

From your distro package manager installation of qemu-kvm and all of deps needed... Some distros setup everything for you, some others half of them and  the other half you must do them manually.So, Find your distro way to install properley qemu.


NOTE: After you install qemu-kvm libvirt etc from your package manager, in case you encounter below error:
```
qemu-system-x86_64: command not found
```
This way you can install it to some of distros...find yours if its not here:
<br>

| `LINUX DISTRBUTION`        | `COMMAND`                            |
|----------------------------|--------------------------------------|
| `Debian`                   | `apt-get install qemu-system-x86`    | 
| `Ubuntu`                   | `apt-get install qemu-system-x86`    | 
| `Arch Linux`               | `pacman -S qemu-headless`            | 
| `Kali Linux`               | `apt-get install qemu-system-x86`    | 
| `Fedora`                   | `dnf install qemu-system-x86-core-2` | 
| `Raspbian`                 | `apt-get install qemu-system-x86`    | 
| `........................` | `..................................` | 



Everything else you need is in the script...
### read it!


Good Luck ;)


PS: we will not need virt-manager, we can do our job in a Linux-terminal... it doesnt hurt :) 
