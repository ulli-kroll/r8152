<u>**r8152 for linux**</u>

linux kernel driver for RTL8152/RTL8153/RTL8156 devices.

**Building and install driver**

for building type  
`make`  

for load the driver  
`sudo insmod r8152.ko`  

PLEASE NOTE !  
you must maybe remove upstream module 

**STATUS**  
Currently as educational driver,  

at leaat you need kernel version v5.7  
sorry guys I don't care If use older ones  

**TODO**, will work on if I have enough time,  
- ethtool support for 2500Mpbs in kernel ?  
- 2500 Mbps only on USB3 interfaces flag ?  
- minor crosscompile check ?  
- rip out firmware blobs  
- prepare for upstream ?  

Hans Ulli Kroll <linux@ulli-kroll.de>
