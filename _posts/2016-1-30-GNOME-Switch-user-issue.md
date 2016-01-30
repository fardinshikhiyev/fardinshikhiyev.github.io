---
layout: post
title: GNOME 3.18 switch user issue fix
published: true
category: Linux
---

Hi everyone! It's my first blog post here and i'm a little excited(i mean a lot LOL). I want to give a solution to an issue which i figured out how to solve in GNOME 3.18. The problem is, when i tried to switch user in GNOME, gdm was freezing and screen was turning into black so i couldn't do anything and lose all my work. The only option was rebooting. If this affects you too, try the following solution.

- Open a terminal window and type 

`sudo nano /etc/gdm/custom.conf`

You can change nano to your favorite text editor. It's just the simplest one.

- Then enter your password and find **`#WaylandEnable=false`** line and uncomment the line. Then save your config file(`CTRL+O` in nano) and everything is OK now! 

![Final view of the config file]({{  site.url }}/images/Screenshot-2016-01-30%2020-56-38.png)

Comment below if it helped to solve your issue or not. Cheers :) 



