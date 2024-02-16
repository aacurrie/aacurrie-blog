---
date: 2024-02-12
authors: [aacurrie]
description: >
  [ PUT DESCRIPTION ]
categories:
  - Blog
links:
  - plugins/blog.md
---

# How Invasive Is Too Invasive?

![image](https://baylorlariat.com/wp-content/uploads/2021/03/lariat-lockdown-browser-copy.png)

In the previous post, we talked about the invasive nature of anti-cheat systems for games in order to prevent users from loading cheats. Similarly, proctoring software aims to stop a differnet kind of cheater: test cheaters. Software proctors such as Respondus Lockdown Browser, Examity, Honorlock typically require deep access into your operating system and system level features. They also may have access to your webcam or microphone to hopefully prevent cheaters with second monitors or using someone else to take the exam. 

<!-- more -->

In a technical sense, software protoctors such as Lockdown Browser *__are__* malware. They may not have the same maliciuos intentions as malware we commonly know, but they exhibit extremely similar behavior to rootkits or any other unauthorized software. Just as malware digs through your files and directories searching for personal information, proctoring software does the same just with a different purpose.

#

![lockdown](https://www.montclair.edu/responsive-media/cache/itds/wp-content/uploads/sites/248/2021/11/LDBWebcamCheck.png.3.1x.generic.jpg)

<center><span style="color: #8c8c8c; font-family: Babas; font-size: .9em;">Typical checks of proctoring software</span></center>

#

As proctoring software delves deep into your system, it raises significant security concerns:

- __Vulnerabilities and Exploits__: Like any software, proctoring tools are susceptible to bugs, vulnerabilities, and exploits. If not properly secured, these weaknesses could be exploited by malicious actors to gain unauthorized access to your system, compromising its integrity and exposing your data to potential theft or manipulation

- __Third-Party Risks__: Proctoring software is often provided by third-party vendors, raising concerns about data handling practices and security measures implemented by these entities. Inadequate security measures or data breaches within these organizations could expose sensitive information collected during examinations to unauthorized parties.

- __System Instability__: The deep integration of proctoring software into the operating system can sometimes lead to system instability or conflicts with other software applications. This may result in performance issues, crashes, or unintended consequences that severely affect a user's system