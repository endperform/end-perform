---
title: "Pi Home Server Time"
date: 2020-06-01T22:20:48-04:00
draft: false
tags: ["projects", "linux", "pi"]
---
*Note: I'll update on life in a later post*

Recently the Raspberry Pi foundation released a beta firmware that enables booting from USB, and it's something I've been waiting on. I recently took the Pi 4 out of service as a [Pi-Hole][1] since I started using [NextDNS][2] for all of my devices which utilizes a lot of the same blocklists that Pi-Hole does. So, after a bit of fiddling around and following instructions found on [this blog post][3], I was up and running from a 240GB SSD, and I installed Docker. What am I using it for?

**Use #1: Bookmark Server**  
I wanted somewhere to stash bookmarks that I regularly visit as well as some other 'check out later' links. I opted to use [LinkDing][4] via Docker container. I won't go into its usage, but it meets my needs. Just one bookmark in my browsers (I use multiple) and I can access my sites from any machine on my network.

**Use #2: Always-on Torrent Box**  
I set up Deluge and the web interface. I don't use it very often, but it's nice to have a torrent client running in a centralized location. I have a mountpoint from my NAS mounted on it, and I'm currently seeding my favorite Linux distributions. 

**Future Uses**  
In the future, I plan to set it up to push backups to Backblaze from the NAS. This will allow me backup to the NAS from my other machines, then let the Pi push the backups overnight. I'll most likely install a webserver on it as well to give me a place to play around.

[1]: https://pi-hole.net
[2]: https://nextdns.io
[3]: https://tynick.com/blog/05-22-2020/raspberry-pi-4-boot-from-usb/
[4]: https://github.com/sissbruecker/linkding
