---
layout: post
title: Some basic shell commands, for newbies 
subtitle: Just a little help, for you, newbie to linux, get closer to your best friend, the terminal.
date: 2021-04-23
tags: [shell, guide]
---

## Basic shell commands, for newbies in linux.

When I started into the Linux world, especially talking about the command line, I've found pretty hard to find a good guide to all the basics that need to know. So, I'm here to do ( or at least try to ) make a simple guide with some stuff about the command line, giving you a good startpoint into it.


### First of all, some terminology that you'll need to know

+ ***Terminal =*** A terminal is simply an interface to interact with your computer. Basically, its nothing but an empty program. It needs a shell to work.
+ ***Shell =*** A shell is a interactive text interface for the user, and the **Terminal** is the tool most often used to run stuff using the shell. The combo between shell and terminal provides you, the fellow user, the powerful **"CLI"**, or *command-line-environment*. There are many options of shells, but most linux distributions come with **Gnu Bash** or **B**ourne **A**gain **SH**ell, the most popular one in use at the moment. If you are using other shell (which can be check with the command `echo $SHELL`) don't worry, everything on this guide will still work.

Here is what you will see when you fire up a terminal and consequently, a shell:

```sh
# this is a comment, that I'll be using to guide you along this guide.
[user@hostname $] <-- The prompt, where you enter commands 
# On this guide, I'll short the prompt to: 
[$] ( because is easier to type )
```

And finnaly, the **The Most Important Thing That You'll Read On This Guide**[^1] you have to always be willing to read documentation and official manuals when encontering a problem or struggling to learn something. Don't go around annoying others for help. Some common things when having issues include:
  * Reading the offcial manual of the program, that can be easily accessed by just running `man *program*` on terminal.
  * Searching through [Github](https://github.com) issues the problem that you're actually having with the program.
  * Searching on forums, like [Stack Overflow](stackoverflow.com) or forums made by linux distribuitions, like [GentooForums](https://forums.gentoo.org/).
  * Searching through amazing distro wiki's, like [Gentoo Wiki](https://wiki.gentoo.org/) or [Arch Wiki](wiki.archlinux.org).
  * Searching or making posts on [Reddit](reddit.com) communities.

**Following this simple steps, you are going to improve and learn better and faster than any other way, like seeing an 2 hour tutorial on youtube.**
  
Differently than most linux users think, that's not the best way to learn. In fact, troubleshooting, and searching for solutions to ur problems makes you learn in a pratical way.


[^1]: Always remember: **RTFM =** Read The Fucking Manual!
