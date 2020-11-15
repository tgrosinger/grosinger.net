---
author:
  name: "Tony Grosinger"
date: 2020-11-15
type:
- post
- posts
title: Advanced Markdown Tables
cardCategory: Project
shouldLink: true
weight: 20
---

Improved navigation, formatting, manipulation, and even formulas in Markdown tables.

<!--more-->

I am an avid proponent of maintaining a personal wiki, or personal knowledge
base. This can be as simple as a paper journal, or as complicated as programs
like DEVONthink and ROAM Research. Over the last 10 years I have experimented
with nearly a dozen approaches, but the last few have been fairly minor
tweaks.

To reduce the wiki churn, I realized I needed a method which could be easily
converted into any format in the future, was universally supported, and was
relatively extensible. I tried out [org-mode](https://orgmode.org/) for a
while, but even with Evil mode, I didn't enjoy spending time in emacs.

I completed what I hope to be my last wiki migration over the 2020 summer,
switching to Markdown. It's simple, it's used everywhere, and it seems to be
gaining ground in the personal wiki space rapidly. But leaving org-mode did
have some shortfalls. It has amazing utilities for editing tables.

Building off of the excellent library started by
[susisu](https://github.com/susisu), I have been working on adding advanced
features to tables in Markdown. With an editor that has this library
incorporated (often possible though a plugin), Markdown tables become nearly
as powerful as they are in org-mode. Automatic formatting,
adding/moving/removing columns, sorting, and now even some spreadsheet
capabilities are all possible in plain-text Markdown tables.

![Basic functionality](https://raw.githubusercontent.com/tgrosinger/advanced-tables-obsidian/main/resources/screenshots/basic-functionality.gif)

I hope this enables you to make the jump to a Markdown-based wiki.

I recommend [Obsidian](https://obsidian.md/).
