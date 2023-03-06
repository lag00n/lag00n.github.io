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
-   ***Shell =*** A shell is a interactive text interface for the user, and the **Terminal** is the tool most often used to run stuff using the shell. The combo between shell and terminal provides you, the fellow user, the powerful **"CLI**" or *command-line-environment*. There are many options of shells, but most linux distribuitons come with **Gnu Bash**, or **B** ourne **A** gain **SH** ell, the most popular one in use at the moment. If you are using other shell (which can be check with the command `echo $SHELL`) don't worry, everything on this guide will still work.

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

**Following this simple steps, and principally, effectively learning while you search for solutions, you're going to improve and learn better and faster than any other way, like seeing an 2 hour tutorial on youtube.**


## Now, without futher ado, let's get closer to your shell


### How do a shell work?

Basically, your shell allows you to run commands on terminal, and even arrange them using operators for scripting purposes. However, your shell has access only to binaries that are located in your `$PATH`. To discover which folders are part of your `$PATH` you can run the following command:

{% highlight sh %}
[$] echo $PATH
{% endhighlight %}


### Shell configuration

Bash configuration can be easily done by just modifying a file called `.bashrc`, that can be found on your `$HOME` directory (which is `/home/{your-username}`, but you can check that using `echo $HOME` <a id="flex"></a>). In this file, you can change a lot of stuff on your shell, from changing his appearance to creating aliases and changing environment variables.
On zsh, the configuration file can be found on the same place than `.bashrc`, while on fish is located at `$HOME/.config/fish/config.fish`

> Most shells has a system-wide config, located at `/etc`, but It's completely **not recommended** to change that file instead your local one.


### Autocomplete

All shells has **built-in autocomplete**, so, instead typing a long folder/program name, you can just type a few words and press `tab` key, then you shell is going to auto-complete the rest of the name for you. If there is more than one possibility, your shell is going to show you all of them, so you can choose which one do you want.


### Some global simple aliases

`..` is an alias for the parent folder of the directory you're currently working on, while `.` is a alias for the folder that you're currently occuppying. You can use these aliases to save some time typying the entire path to a folder.
`~` is a alias to your $HOME directory<sup><a id="fnr.2" class="footref" href="#fn.2">2</a></sup>, so, instead of typing `/home/{your-username}/path/to/a/file`, you can simply type `~/path/to/a/file`

# Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup> Always rembember: **RTFM =** Read The Fuc\*\*\*\* Manual!

<sup><a id="fn.2" href="#fnr.2">2</a></sup> As explained [Here.](https://lag00n.github.io/bash-for-begginers#flex)
