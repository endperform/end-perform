+++
title = "Back to Linux"
date = 2019-07-12
tags = ["linux", "tech"]
+++
On Monday, I wiped my main drive of Windows and installed Linux (Arch, if you'd like specifics) after taking a couple of weeks to do some research with regards to what I would miss by moving to Linux as my main operating system. Since others may be interested in what I ended up doing, I figured I would write about how I went about this.

Windows 10 was working alright for me, but it was getting to be a bit annoying at times and I wanted to be able to jump into some projects head-first. Sure, there's WSL or VMs, both of which I tried for some time, but they didn't seem to really fit. Trying to keep Windows software updated was a bit of a process, and trying to corral files in different places was getting to me. So, the research began into what it would take to convert. 

### Productivity and Creativity  
This was number 1 on my list. Creativity includes my photography work and my little [streaming channel][1] which I recently shifted focus from gaming to more of a tech-based channel. My photography requirements are simple: edit Nikon and older Adobe RAW formats (NEF and DNG), archive them and export them as needed. I had forgotten I have a license for Aftershot Pro 3, which actually has a Linux native version. The only issue there is that it does not handle the Adobe DNG from Lightroom. I do, however, also have a license for DxO Photolab 2 but unfortunately there is no Linux native version of it and it does handle the older DNGs. I tried a few of the open source solutions, such as Darktable, but they felt a little clunky. Solution? Windows 10 in a virtual machine. I was planning on doing this anyway, so I installed it, then Photolab and shared a directory from the host OS to Windows and it works well enough. Honestly going forward I can work with just Aftershot Pro 3, but it's nice I have this option.  

For streaming, [OBS][2] has a Linux native version, so that's sorted out. I haven't run a full stream, but local testing seems to show it's going to work just fine. Unfortunately the Streamdeck I have has no Linux software, but after thinking about it, I hardly ever used it anyway. There are some third-party Python modules, so I might work on my own custom interface for fun. It's not a dealbreaker, though.  

Other creative things include learning a new programming language and writing some software. This is both for fun and for future career advancement opportunities and I figured I might as well work in the environment that I'm in at work anyway.

### Gaming  
Ah yes, games. I installed Linux on a spare SSD and then installed Steam, Wine and Overwatch. All of them worked well enough, so that was pretty much all of the convincing I needed. I will be keeping a Windows install around on the spare SSD for those games I absolutely cannot get working (hi, Division 2), but I suspect I'm not going to be using it that much. All of the emulation I do have Linux options, so that's no worry there. 

### Odds and Ends  
My desktop PC has an NZXT Kraken X62 CPU cooler which has Windows control software. I thought at first I might be out of luck, but after a bit of poking around online, I found the [gKraken][3] project. Someone wrote some drivers and put a nice little graphical frontend on them which allows me to set profiles and monitor the CPU cooler. It works great, too. 

### Issues I had  
* Mounting my NAS took a bit of command-line magic, but it works now. It automounts on startup and is available to me
* Dual monitors were a slight headache until I reversed the Displayport cables on the video card

### Conclusion  
The switch wasn't bad at all. The things I need to work, do. I'm not going to be one of those obnoxious Linux users that turns their nose up at someone using Windows. I'm all about using the tools that are best for you. If that's Windows, awesome! If that's Mac or Linux? Also awesome!.

[1]: https://twitch.tv/justxanny
[2]: https://obsproject.com/
[3]: https://gitlab.com/leinardi/gkraken
