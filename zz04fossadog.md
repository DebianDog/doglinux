---
layout: menu
title: FossaDog
image: css/fossa.png
---
---
     
### FossaDog (Ubuntu 20.04 'Focal Fossa' LTS) 64 bit        
(Ubuntu minimal "live")

**Updated 2020-11-15** Some bugfixes      
Update 2020-09-07 Now with UEFI support.           

**FossaDog is a fork of "DebianDog"** with the difference that it's Ubuntu based.   
See also for Debiandog history: [Here](https://debiandog.github.io/doglinux/zz07about.html)     
DebianDog full credits: [Here](https://github.com/DebianDog/Wheezy/blob/master/Credits.md)    

[Thread on new Puppy Linux forum](http://murga-linux.com/puppy/viewtopic.php?f=58&t=478)    

**[See here for Changes and Fixes information](http://murga-linux.com/puppy/viewtopic.php?p=2476#p2476)**     

Full access to Ubuntu repositories by using apt-get (from terminal) or from Synaptic Package Manager (GUI) 
    
### Login details:    
**root** with password **root**        
**puppy** with password **puppy**    

**Specifications:**   (Updated 2020-11-15)   
Built from scratch by using debootstrap  (previous was upgrade from BionicDog).    
Kernel: 5.4.0-53-generic    
Boot Method: porteus-boot , see examples [Here](https://github.com/DebianDog/FossaDog/raw/master/Examples-boot-codes.txt)   
Default WM - OpenBox    
(with different choice of Desktop modes: tint2 icon-panel, cairo-dock or rox-pinboard icons, to choose, run 'Desktop Manager' from Menu)    
Tint2 bottom panel or cairo-dock.       
Default File Manager - pcmanfm with option to use rox.    
Default Internet Browser - Firefox Quantum latest version (running by default with apulse to enable sound).    
Menu provided by Obmenu-generator (perl script)  

Full LZ4 squashfs support (compression and loading modules)    

Systemd is enabled by default.    

### Download : **Updated 2020-11-15** Some bugfixes    
Update 2020-09-07, now with UEFI support, many thanks to @jamesbond from Puppy Linux forum      
Iso 64-bit, all fimware included (e.g. for WiFi): [FossaDog-2020-11-15_64-bit-UEFI.iso](https://github.com/DebianDog/FossaDog/releases/download/0.1/FossaDog-2020-11-15_64-bit-UEFI.iso) **Size: 566MB**            
Md5sum: [FossaDog-2020-11-15_64-bit-UEFI.md5](https://github.com/DebianDog/FossaDog/releases/download/0.1/FossaDog-2020-11-15_64-bit-UEFI.md5)             

Thanks very much to everyone who has been involved with DebianDog, specially Toni (saintless), William (mcewanw), Terry (sunburnt), Bill (rcrsn51), dancytron, belham2, backi, wiak, The Flying Cat and all who helped by giving feedback on the DebianDog and XenialDog threads.   
    
**Screenshots:**  

Openbox with tint2-panels:  
![OpenBox](https://github.com/DebianDog/FossaDog/raw/gh-pages/fossadog-tint2.jpg)  

Openbox with Cairo-dock:  
![OpenBox](https://github.com/DebianDog/FossaDog/raw/gh-pages/fossadog-cairo-dock-roxpinb.jpg)  

Pcmanfm + lxpanel:  
![OpenBox](https://github.com/DebianDog/FossaDog/raw/gh-pages/fossadog-pcmanfm-lxpanel.png)  
