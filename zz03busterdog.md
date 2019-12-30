---
layout: menu
title: BusterDog
image: css/devuan.png
---     

---
<br> 
BusterDog, based on the Debian 'Buster' branch but **without systemd**.  
It's using special method (taken from **AntiX**) to avoid systemd by replacing systemd with 'elogind'.  
(and more, e.g. libsystemd replaced by libelogind)      
[Forum thread](http://murga-linux.com/puppy/viewtopic.php?t=117255){:target="_blank"}     
See [Here](https://debiandog.github.io/MakeLive/Readme-build-busterdog.html){:target="_blank"} for a **Busterdog build system**.    

### 32 and 64 bit ISO's, download:  [Here](https://github.com/DebianDog/BusterDog/blob/master/README.md#busterdog--build-system){:target="_blank"}            
(see specifications below)                   
      
DEVX and Firmware squashfs modules: [Here](https://github.com/DebianDog/BusterDog/releases/tag/v0.2)         

Built from scratch by using debootstrap and remastered afterwards.     

Custom repository: [32-bit](https://doglinux.github.io/busterdog/i386/) [64-bit](https://doglinux.github.io/busterdog/amd64/)   

### Login details:
**root** with password **root**    
**puppy** with password **puppy**

**Specifications:**          
Kernel: 4.19.0-6 (the kernel is separate module)         
Choice of Boot Methods: porteus-boot and live-boot v3 (see for options [Here](https://github.com/DebianDog/BusterDog/raw/master/Examples-boot-codes.txt))  
(EDIT: See post [Here](http://murga-linux.com/puppy/viewtopic.php?p=1015160#1015160) for how to boot with older kernel 3.16 if possibly your hardware is too old for booting v4.19)  
Default WM - OpenBox, with Desktop choices (run 'Desktop Manager' to choose):  
- Tint2 panels    
- PcmanFM providing the Desktop and lxpanel    
- Tint2 bottom panel and rox-pinboard providing the Desktop

Option to switch to JWM window-manager                  
Default File Manager - PcmanFM with option to use rox.        
Default Internet Browser - Palemoon.   

---      
 
**Screenshots:**   
  
Openbox with tint2 panels:         
![SCREENSHOT](https://github.com/DebianDog/BusterDog/raw/master/busterdog1.jpg)        
Openbox with PcmanFM and lxpanel:       
![SCREENSHOT](https://github.com/DebianDog/BusterDog/raw/master/busterdog2.jpg)         
 