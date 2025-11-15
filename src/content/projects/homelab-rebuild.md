---
title: "Server rebuild"
description: "Homelab rebuild"
pubDate: 2025-11-15
heroImage: "https://images.cyroth.com/PXL_20251115_093316231.jpg"
---

My homelab server has been running Debian over 4 full updates and 3 different computers. Needless to say, it's built up a **lot** of cruft.

I'm trying to keep it slim and install only the things I need as I need them and trying to keep to the [DontBreakDebian](https://wiki.debian.org/DontBreakDebian) principle. (Side note, already failed due to an ancient Rclone with nothing in backports)

So far I've reinstalled:
* Docker
* Rundeck
* Chrome remote desktop
* Nvidia drivers and container toolkit
* Handbrake, Picard and Sound Converter (for media operations)

By far the biggest drama I had was re-installing Rundeck due to outdated guides on the official site. I've addressed it [here](https://cyroth.dev/guides/linux/rundeck-install/)