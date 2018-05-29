---
layout: menu
title: BionicDog
image: css/Bionic.png
---

---
 
### BionicDog (Ubuntu 18.04 'Bionic Beaver' LTS) 32 bit and 64 bit  
(Ubuntu minimal "live")

**BionicDog is a fork of "DebianDog"** with the difference that it's Ubuntu based.   
See also for Debiandog history: [Here](https://debiandog.github.io/doglinux/zz07about.html){:target="_blank"}   
DebianDog full credits: [Here](https://github.com/DebianDog/Wheezy/blob/master/Credits.md){:target="_blank"}  

[Thread on Puppy Linux forum](http://murga-linux.com/puppy/viewtopic.php?t=113210){:target="_blank"}   

**[See here for Changes and Fixes information](http://murga-linux.com/puppy/viewtopic.php?p=989364#989364)**   

Full access to Ubuntu repositories by using apt-get (from terminal) or from Synaptic Package Manager (GUI)

Openbox is the main window-manager, the GUI setup is very much like [DebianDog Jessie 64-bit](zz02debiandog64.html)  
    
### Login details:    
**root** with password **root**        
**puppy** with password **puppy**    

**Specifications:**    
Built from an absolute minimal Ubuntu by using debootstrap.    
Kernel: 4.15.0-15-generic    
Boot Method: porteus-boot , see examples [Here](https://raw.githubusercontent.com/fredx181/bionicdog/gh-pages/Examples-boot-codes.txt)   
Default WM - OpenBox    
(with different choice of Desktop modes: tint2 icon-panel, cairo-dock or rox-pinboard icons, to choose, run 'Desktop Manager' from Menu)    
Tint2 bottom panel or cairo-dock.       
Default File Manager - pcmanfm with option to use rox.    
Default Internet Browser - Firefox Quantum (running by default with apulse to enable sound).    
Menu provided by Obmenu-generator (perl script)  

Full LZ4 squashfs support (compression and loading modules)    

Systemd is enabled by default.    

**Download:**    
Iso 32-bit: [BionicDog32_2018-04-21.iso](https://github.com/fredx181/bionicdog/releases/download/v1.0/BionicDog32_2018-04-21.iso) **Size: 305MB**          
Md5sum: [BionicDog32_2018-04-21.md5](https://github.com/fredx181/bionicdog/releases/download/v1.0/BionicDog32_2018-04-21.md5)     
DEVX 32-bit: [61-DEVX-BionicDog32_2018-04-21_i386.squashfs](https://github.com/fredx181/bionicdog/releases/download/v1.1/61-DEVX-BionicDog32_2018-04-21_i386.squashfs)    

Iso 64-bit: [BionicDog64_2018-04-21.iso](https://github.com/fredx181/bionicdog/releases/download/v1.0/BionicDog64_2018-04-21.iso) **Size: 314MB**          
Md5sum: [BionicDog64_2018-04-21.md5](https://github.com/fredx181/bionicdog/releases/download/v1.0/BionicDog64_2018-04-21.md5)     
DEVX 64-bit: [61-DEVX-BionicDog64_2018-04-21_amd64.squashfs](https://github.com/fredx181/bionicdog/releases/download/v1.1/61-DEVX-BionicDog64_2018-04-21_amd64.squashfs)  
    
Locales: [99-locales-BionicDog-2018-04-21.squashfs](https://github.com/fredx181/bionicdog/releases/download/v1.1/99-locales-BionicDog-2018-04-21.squashfs)  

Firmware (e.g. for WiFi): [99-bionic_linux-firmware.squashfs](https://github.com/fredx181/bionicdog/releases/download/v1.1/99-bionic_linux-firmware.squashfs)  

BionicDog custom package repository: [Here 32-bit](https://fredx181.github.io/bionicdog/Packages-i386/){:target="_blank"} and [Here 64-bit](https://fredx181.github.io/bionicdog/Packages-amd64)         

Thanks very much to everyone who has been involved with DebianDog, specially Toni (saintless), William (mcewanw), Terry (sunburnt), Bill (rcrsn51), dancytron, belham2, backi, wiak, The Flying Cat and all who helped by giving feedback on the DebianDog and XenialDog threads.   

<br>
**YouTube Review:** thanks @sneekylinux !  
{::comment}   
[![Bionic Dog 64...It's No Feline..!!](http://img.youtube.com/vi/r9fuNL3gPMQ/0.jpg)](https://youtu.be/r9fuNL3gPMQ "Bionic Dog 64...It's No Feline..!!")    
{:/comment}   

<iframe width='480' height='380' src="https://www.youtube.com/embed/r9fuNL3gPMQ" frameborder="0" allowfullscreen></iframe>     

**Screenshots:**  

Openbox with tint2-panels:
![OpenBox](https://github.com/fredx181/bionicdog/raw/gh-pages/screenshots/bionicdog-tint2-panels.jpg)

Openbox with Cairo-dock:
![OpenBox](https://github.com/fredx181/bionicdog/raw/gh-pages/screenshots/bionicdog-cairo-dock.jpg)
   
