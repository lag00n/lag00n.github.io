---
layout: post
title: Basic shell guide, for linux newbies
subtitle: Just a little help, for you, newbie to linux, get closer to your best friend, the cli.
date: 2021-04-23
tags: [shell, guide]
---


# Table of Contents

1.  [Welcome to my attempt into making a good CLI guide&#x2026;](#orgbcf0bed)


<a id="orgbcf0bed"></a>

# Welcome to my attempt into making a good CLI guide&#x2026;

When I started into the Linux world, especially talking about the command line, I've found pretty hard to find a good guide to all the basics that I needed to know. So, I'm here to do ( or at least try to) make a simple guide with some stuff about the command line, giving you a good startpoint into it.


## First of all, some terminology that you'll need to know

-   ***Terminal =*** A terminal is simply an interface to interact with your computer. Basically, it's nothing but an empty program, that need a shell to work.
-   ***Shell =*** A shell is a interactive text interface for the user, and the **Terminal** is the tool most often used to run stuff using the shell. The combo between shell and terminal provides you, the fellow user, the powerful **"CLI**" or *command-line-environment*. There are many options of shells, but most linux distribuitons come with **Gnu Bash**, or **B**ourne **A**gain **SH**ell, the most popular one in use at the moment. If you are using other shell (which can be check with the command `echo $SHELL`) don't worry, everything on this guide will still work.

Here is what you'll see when you fire up a terminal and consequently, a shell:

{% highlight sh %}
# this is a comment, that I'll be using to guide you along this guide.
[user@hostname $] <-- The prompt, where you enter commands
# On this guide, I'll short the prompt to:
[$] (because is a lot easier to type)
{% endhighlight %}

And finnaly, the **The Most Important Thing That You'll Read On This Guide**<sup><a id="fnr.1" class="footref" href="#fn.1">1</a></sup> you have to always be willing to read documentation and official manuals when encontering a problem or struggling to learn something. Don't go around annoying others for help. Some common things when having issues include:

-   Reading the official manual of the program, that can be easily accessed by just running `man *program*` on terminal.
-   Searching through [Github](https://github.com) issues the problem that you're actually having with the program.
-   Searching on forums, like [Stack Overflow](https://stackoverflow.com) or forums made by linux distribuitions, like [Gentoo Forums](https://forums.gentoo.org).
-   Searching through amazing distro wiki's, like [Gentoo Wiki](https://wiki.gentoo.org) or [Arch Wiki](https://wiki.archlinux.org).
-   Searching or making posts on [Reddit](https://reddit.com) communities.

**Following this simple steps, you're going to improve and learn better and faster than any other way, like seeing an 2 hour tutorial on youtube.**

# Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup> Always rembember: **RTFM =** Read The Fuc\*\*\*\* Manual!
