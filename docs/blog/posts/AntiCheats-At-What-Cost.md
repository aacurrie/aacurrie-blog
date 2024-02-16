---
date: 2024-02-11
authors: [aacurrie]
description: >
  [ PUT DESCRIPTION ]
categories:
  - Blog
links:
  - plugins/blog.md
---

# AntiCheats - At What Cost?
![Kernel Levels](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Priv_rings.svg/600px-Priv_rings.svg.png)
### What are Kernel Levels?
Computers have hierarchical protection domains called protection rings. The computer's operating system offers varying degrees of system resource to certain access through these rings. This hierarchy is enforced at a hardware level typically by the CPU which encorporates distinct modes in its microcode. As seen in the image above, rings are ordered numerically from most priviledged (Ring 0) to least priviledged (highest numbered ring). Since Ring 0 has the highest level of priviledge, it has direct access to physical hardware components.

<!-- more -->

![Kernel Levels](https://support-valorant.riotgames.com/hc/article_attachments/6952978273427)

Some anti-cheats require kernel-level access to peferom their functions. One of the most prevelent anti-cheats, Vanguard, is used by the popular game Valorant, which has over 28 million monthly players. In order for the game to run, Valorant not only requires the Vanguard anti-cheat to run at system boot, but to be active entirely while a computer is on. By starting before any other program or process, kernel-level anti-cheats can catch cheats before they even run. While the system is actually on, these anti-cheats are able to keep tab on the computer's system processes and how they interact with application memory, preventing cheats from reading or writing memory while the game is running 

![prevention](https://support-valorant.riotgames.com/hc/article_attachments/6952894213907)

### But that's what we want, right?

In truth, this raises some serious security concerns. These types of anti-cheats are basically root-kits and can montior everything you can do on your computer if used incorrectly. Or, maybe even worse, use your system's resources for their own profit such as [mining for bitcoin](https://www.wired.com/2013/11/e-sports/). On common criticisms of Vangaurd is that its parent company is a subsidiary of Tencent, a Chinese technology conglomerate which, like many other large Chinese companies, has [ties with the CCP](https://www.reuters.com/world/china/beijing-takes-golden-share-tencent-subsidiary-records-show-2023-10-19/) But the problem may not even come from the gaming company. If a third party were gain access the an anti-cheat through a company leak, they would have infinite access to your system processes.