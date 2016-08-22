---
layout: post
title: Speed-up your oh-my-zsh startup time
published: true
category: Linux
---

Hi everybody! It's been long since my last post. I will show a quick and simple way of speeding up your oh-my-zsh startup time.
If you have zsh as your default shell with oh-my-zsh, then you have probably noticed that when you open a terminal window 
it takes around 1.5 seconds for zsh to startup. And it's really annoying(time is your most precious resource, right?). So, here's a way to solve this issue.

- Open **`~/.zshenv`** file with your prefered text editor(if this file doesn't exist, create it under the **`home(~)`** directory). 
- If you have this file already, then just append **`skip_global_compinit=1`** to the file.
- If you don't have the file and you created it yourself, make sure it looks [like this](https://goo.gl/1mNMH3).

Cheers :)
