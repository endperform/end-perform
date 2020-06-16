---
title: Debian 10 on a Thinkpad W540
date: 2019-10-25 09:35:00
tags:
- tech
- linux
- thinkpad
---
I'm a fan of the older Thinkpads. They work, they're not super-expensive and they fit my needs perfectly. My current Thinkpad is the following:

* Thinkpad W540 i7-4800MQ
* 32GB RAM
* 500GB SSD (Primary)
* 250GB SSD in the superbay (replaced the DVD drive)


For some time I was running Windows 10 on it, but given its main purpose in life is a mobile workstation for when I'm on call, and my job is primarily Linux-based, I decided to see how Linux would run. I'm quite happy with the results, as the laptop actually runs a bit better on Linux and as a bonus, I still have Windows 10 in a VM. My environment is Debian 10 using the Mate desktop. I installed via the non-free live CD available on Debian's website, and the initial installation took about 20 minutes or so. This particular Thinkpad has a 3k (2880x1620) display, which is problematic by default in some desktop environments. Luckily it seems Mate handled it out of the box and set scaling accordingly, which is nice, but just keep in mind that you might have to manually configure scaling and/or font DPI. Mate, Budgie and I believe KDE Plasma will handle it automatically. I can't speak for Gnome, but I'm fairly sure it will handle it as well.  

After install, everything was working. Sound, trackpad, bluetooth and wifi. I haven't tried the webcam or fingerprint reader, but they were detected by the OS. Basically, everything is working as it should. Additionally I installed Bumblebee in order to utilize the Intel graphics by default but allow for use of the nVidia graphics if I need the additional power and finally I installed TLP which will assist with power consumption. The laptop is quite usable, but I still have some things to do to get it ready for work. More on that later.  

Long story short, Thinkpads are decent machines and they run Linux with no trouble.





