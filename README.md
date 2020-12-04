<u>**r8152 for linux**</u>

linux kernel driver for RTL8152/RTL8153/RTL8156 devices.

**Building and install driver**

for building type  
`make`  

for load the driver  
`sudo insmod r8152.ko`  

<u>PLEASE NOTE !</u>  
you must maybe remove upstream module 

Tested on x86_64 and arm64 devices  

**NOTE ABOUT MASTER BRANCH**

due the fact Realtek releases it's r8152 driver  
as tar archive, it's not possible to make  
the master branch **pullable**  
master will follow the most recent development branch.  

you should do  
`git reset origin/master --hard`  

soyy for the inconvenience


**STATUS**  
Currently as educational driver,  

at leaat you need kernel version v5.7  
sorry guys I don't care If use older ones  

**TODO**, will work on if I have enough time,  
- ethtool support for 2500Mpbs in kernel ?  
- catch up with upstream driver to
- rip out firmware blobs / logic  

Hans Ulli Kroll <linux@ulli-kroll.de>
