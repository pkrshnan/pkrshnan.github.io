---
layout: post
title: Clearing the Current Row in Vim
categories: til vim
---

Today I learned something really useful which started saving me a lot of time in vim. Up until recently, whenever I had to replace the content of the current row in a file, I had to:
* Go into Normal Mode
* Use `dd` to delete the current row's contents
* Go to previous row, hit `A` followed by `Enter`
* Start typing relevant content

However, recently I realized that there is a default key-bind of `S`, which will clear the content of the current row and put you into insert mode at the correct indentation level. The workflow then becomes:
* Go into Normal Mode
* Hit `S` to clear row's contents and go into insert mode
* Start typing relevant content

While this may seem like marginal improvements, it's one less step which adds up over time. Hope this helped!

