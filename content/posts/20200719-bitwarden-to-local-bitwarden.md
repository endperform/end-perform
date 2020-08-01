---
title: 'Migrating Passwords from Bitwarden to a Local Bitwarden Instance'
date: 2020-07-19
tags:
- security
- privacy
---
I use a password manager (and really, you should too!) to keep track of my passwords. Up until this point, I was using [Bitwarden][1], which is a fine service, but I learned that there were a few options for local / self hosting so I started to explore. My current home server is a Raspberry Pi 4, 4GB model running from an SSD via USB adapter. It doesn't do a lot of heavy things (future writeup on it coming), and it seemed like a good opportunity to look at migrating to a local Bitwarden instance. Further research brought me to the [Bitwarden_rs][2] project, which is a lightweight implmentation of Bitwarden written in Rust, which is what I decided to deploy on via a Docker image. The project's wiki has some good instructions on how to get it up and running complete with SSL, which is something you'll need if you're using the mobile apps (which I do), as well as the browser extensions.  

Once up and running, I exported the data from my online Bitwarden account and imported it into the local instance with no issues. A couple of minor configuration changes for the apps and extensions, and I was up and running with my local Bitwarden installation, no passwords sitting out in the wild. Obviously it's a personal preference on whether you use and trust a service, and as I mentioned I had no trust issues with Bitwarden, I just wanted to move things locally so I can take backups and have it available to me at all times.  

[1]: https://bitwarden.com
[2]: https://github.com/dani-garcia/bitwarden_rs
