# Qemu-slackware
A simple script which running in any Linux system.
Download and install a Qemu installation of Slackware 15.
Also include the command to start manually from your terminal your QEMU virtual Slackware installation in UEFI mode. 

Download: open a terminal:
```
wget https://raw.githubusercontent.com/rizitis/Qemu-slackware/main/qemu-slackware64-15
chmod +x qemu-slackware64-15
```
Everything else you need is in the script...read it!


Good Luck ;)

REQUIRE: From your distro package manager installation qemu-kvm and all deps needed... Some distros setup everything for you some others half of the and the others you should do them manually. Find your distro way to install properley qemu.
After you install qemu-kvm libvirt etc from your package manager, in case you encounter below error:
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


