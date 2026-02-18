---
layout: post
title:  My graduation Project for Technology and Systems
date:   2026-01-26 10:05:55 +0300
image:  /assets/images/blog/post-3.jpg
author: Mario Flores
tags:   Development 
---

**I’ve been diving deep into a CAN Bus simulation project lately, and it’s been a blast seeing how different vehicle components "talk" to each other. For this one, I’m building a virtual dashboard using C++ and Qt in VS Code, designed to visualize real-time data like speed and engine status. The core of the development involves using TCP/UDP sockets and Inter-Process Communication (IPC) to simulate the data flow between virtual ECUs (Electronic Control Units). It’s a great way to bridge the gap between high-level UI design and low-level communication protocols.**

On the technical side, I’ve implemented a DBC parser to handle the message databases, ensuring the system can correctly interpret the raw bus signals. I also integrated JSON/CSV logging so I can track and analyze the data history during simulation runs. To keep everything organized and prevent the usual "it worked yesterday" headache, I’m managing the entire codebase through GitHub for version control and collaboration.

This project has been a perfect way to explore the complexity of automotive communication without needing a physical car in the room. It feels "light" because of the graphical interface, but under the hood, it’s all about managing critical data timing and reliable messaging. It’s definitely one of those projects that makes you appreciate the invisible layers of software that keep modern vehicles running smoothly.