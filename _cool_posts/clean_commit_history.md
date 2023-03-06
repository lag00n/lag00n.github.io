---
layout: post
title: Cleaning the entire commit history in a simple way
subtitle: Maybe you'll find that helpful someday... idk
date: 2023-03-04
tags: [github, git, how2]
---


# Why would I do that?

To be really honest, I don't know. But, I found myself in a situation that all my old commits on this blog repo where kinda ankward mostly because I was really unexperient at web development (not saying that I've improved that much). Without further ado, let's go!

1.  Checkout to another orphan branch;
    
    `git checkout --orphan branch_copy`

2.  Add all the files to this specific branch tracking;
    
    `git add -A`

3.  Commit the files added;
    
    `git commit -am "re-start!"`

4.  Delete the old branch;
    
    `git branch -D master/main`

5.  Rename the current branch;
    
    `git branch -m main/master`

6.  To finish, force-update your repo.
    
    `git push -f origin main/master (depending on the name you put earlier)`

By doing this all your old commit history will disappear from history.

Simple as it is, you just "cleaned" your commit history! Hope it helped.
