---
title: 'Adjusting to Windows for Work'
date: 2020-06-16
tags:
- linux
- windows
- tech
---
Moving from a Linux desktop to a Windows laptop has been an interesting experience as far as work goes. 99% of what I do is Linux-based, so this change by the powers-that-be is an interesting one. I can see where they're coming from, being firmly a Windows shop, but I was hoping we could go a few more years, or at least have the option to install Linux on the new hardware they gave us. Sadly, that wasn't an option, so I set out to make the environment as useful as possible. Here's what I've tried so far.

### Hyper-V
I first looked at Virtualbox, but after some testing I found that Hyper-V seems to be a faster virtualization platform. I have a full-blown Linux install at my disposal, and it works fine, at least until I engage the VPN on the Windows side, then I lose all networking. Normally, this isn't an issue, but with the current work from home situation, it tends to be a pain depending on what I need to do. Still, it's a workable option.

### WSL  
Ah yes, the thing Linux fanboys think Microsoft created to kill Linux. I get a Linux shell without the need to spin up a full VM, and given most of my work is on the commandline, this is a no-brainer. Additionally I recently started using Visual Studio Code at home and found that it integrates with WSL, so should I need to do some scripting work, I can use VSCode to get the job done there.

I will say it's nice having Windows natively; the usual suspects (Teams, Outlook, Office) seem to work better natively than in a VM, so that's an added bonus. All in all, it's not as bad as I thought it would be, and it has me looking at my home setup even more as well.