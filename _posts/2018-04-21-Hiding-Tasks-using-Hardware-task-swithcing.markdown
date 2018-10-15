---
layout: post
title:  "Hiding Tasks using Hardware task swithcing"
img: hardware.gif
date:   2018-04-21 00:00:00 +0200
description: This project was to hide tasks using hardware task switching in Windows 32 bit environment.
---

Recently, malicious mining using CPUs has become a trend - mining which the task is not detected by the users is even more of a threat. In this paper, we focused on discovering a new IA-32 vulnerability and found an undetectable task using hardware task switching method. The created task is undetectable by the operating system and thus hidden from the system user. Although hardware task switching methods are replaced by more convenient software switching methods in the recent years, they still exist on modern computer systems. By manually manipulating hardware task switching, which are directly managed by the CPU, we show that it is possible to create a hidden scheduler aside from the ones created by the operating system. We demonstrate using a simple CPU consumption example that these hidden tasks have potential to evolve into more sophisticated malicious attacks that can go unnoticed by users.

![](hardware.jpg)
There is a task which uses about 55% of CPU usages.
a), b) show the difference of the CPU usages without and with our method. a) shows the usage without our method and b) shows the usage with our method. As shown in Figures, a) shows 55% of CPU usage and b) shows 3% of CPU usages.

If this method is used in servers or clients, it would cause lots of dangers such as malicious mining from people using the servers. 

This is the [poster](Poster.pdf) presented at ASIACCS 2018.

It was also presented at [HITB Amsterdam 2018](https://conference.hitb.org/hitbsecconf2018ams/speakers/kyeong-joo-jung/). [Video](https://www.youtube.com/watch?v=F26hu2q9Nus)

![Poster](Poster.pdf)