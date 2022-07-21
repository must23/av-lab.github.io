---
layout: page
title: Tutorials
permalink: /tutorials
author: MK
show_menu: true
---


## Robotic System Integration | Summer Course 2022
### Day 1-2: Linux Basics
* [Follow the interactive course by The Construct](https://www.theconstructsim.com/robotigniteacademy_learnros/ros-courses-library/linux-for-robotics/) 

### Day 3: Cloud Computing
**Pre-requisites:**
* [Basics of Linux OS](https://www.hostinger.com/tutorials/linux-commands)
* [Fundamentals of computer networks](https://www.ibm.com/cloud/learn/networking-a-complete-guide)

**Parts:**
* [What is Amazon Web Server \(AWS\)](/tutorials/sys1)
* [Setup a clould server using AWS](/tutorials/sys2)
* [Back-end and front-end development crash course](/tutorials/sys3)

### Day 4-7: Robot Operating System
- Day 4 lecture slides: [part 1](ros/Lecture_1_Background.pdf) \|  [part 2](ros/Lecture_2_Introduction.pdf) \| [part 3](ros/Lecture_3_Installation_Setup.pdf)
- Day 5
- Day 6
- Day 7 (morning) 

### Day 7-8: Cloud Robotics
The objective here is to learn how to integrate one or more robots with a custom cloud server so that you can achieve some collaborative functionalities. We will try to perform those tasks using standard Linux tools without resorting fancy custom-made software. The knowledge you gain in this section will be highly transferrable to other domains as well outside robotics.


#### Day 7 (21/7/2022): 
**Pre-requisites:**
* Basics of networking (ports and ips). If you are not familiar about the topic,  [watch this 10 min video](https://www.youtube.com/watch?v=AXrFCbD4-fU) before you proceed
* Understanding of [HTTP protocol](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) (a simple text based application protocol, running on top of TCP ). [Here is an 8 min video tutorial](https://www.youtube.com/watch?v=eesqK59rhGA)
* Domain Name System (DNS), an application layer protocol. [Here is short video tutorial](https://www.youtube.com/watch?v=mpQZVYPuDGU)
* A working installation of Apache web server on your AWS instance from Day 3
  


**Parts: Understanding Web API**

* [Fundamentals of Web API: REST](/tutorials/s4)
* [Building your first API using Common gateway Interface (CGI) on Apache 2](/tutorials/s5)
* [Debugging REST API](/tutorials/s6)


#### Day 8: Custom-made remote tracking system for a robot (22/7/2022)
**Parts:**
- Big Picture
- Debugging your API
- System 
<br>

---
> **Useful Hacks:** 
> * **Linux within Windows**: If you suffer from slow performance of virtual machine, or you don't want to run dual boot system (as you keep going back and forth), you may try Windows Subsystem for Linux (WSL), you can run linux commands within Windows OS, much faster than in virtual machine. [Here is a short tutorial to get started with WSL.](https://docs.microsoft.com/en-us/windows/wsl/about)
> * **Text editor**: you may use 'gedit' to edit files, which is a friendly user interface, but you need a graphical interface running, something that is not always affordable (say you are ssh a remote server). For power users, there is a better alternative that boosts your productivity ten folds beyond any graphical tool. Try vim, a text editor that comes with a learning curve. But it will pay off. [Here is a short tutorial](https://www.youtube.com/watch?v=ggSyF1SVFr4).
> * **Terminal multiplexer** : Suppose you log in to your remote cloud server with your laptop and run a command on the server. Then, suppose you lose internet connection, or the battery dies, or say you decide to switch off the laptop and continue working from home. What happens is that once you lose your ssh connection, your terminal dies with it, and all running processes forked from the terminal will get terminated. Therefore, you need some approach to keep commands running in the background, even if you get disconnected, and then attach to the left terminals. The solution is [terminal multiplixer](https://linuxize.com/post/getting-started-with-tmux/), an interesting software that allows you to resolve the disconnection issue plus more. You can even split your terminal into multiple zones, saving you from opening several terminals. [Here is a video tutorial.](https://www.youtube.com/watch?v=Yl7NFenTgIo) Run ```sudo apt install tmux``` and try it.
> * **Tiling Window Manager**: Linux has a flexible architecture, allowing users to customize practically everything. An important part of any operating system distribution is [window manager](https://en.wikipedia.org/wiki/Window_manager), a piece of software that organizes window placements. The default window manager for Ubuntu is [Gnome](https://release.gnome.org/) (as of 2022). You may customize it as you wish. I personally recommend a different kind of window manager, called tiling window manager. This class of window managers automatically controls window placements into tiles, with minimal user involvement, clicks, and muscle movements. Once you get used to shortcuts, your productivity improves another ten fold (after using vim). [Try i3 window manager](https://i3wm.org/)! Here is a [video tutorial to get started](https://www.youtube.com/watch?v=j1I63wGcvU4).
> * **A more friendly shell**: Shell is a kind of user interface that is based on text only, with no graphics. The default ubuntu shell is called Bash. Similar to graphical interface (e.g., ubuntu, fedoraI), it is a matter of personal taste. personally like ```fish```, or a friendly interactive shell. It comes with a nice auto-complete and a dozen shortcuts (similar to that of ```ipython``` if you used it). [Here is a short tutorial](https://www.youtube.com/watch?v=C2a7jJTh3kU). **Warning**: you cannot run all standard bash commands out of the box. For example, you can't load (or source) bash configuration files. To source any bash config (such as ROS environment setup), you need a fish plugin called ```bass```.[ Clone the GitHub repo and test it yourself](https://github.com/edc/bass).
