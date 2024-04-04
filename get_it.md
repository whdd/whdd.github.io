---
layout: page
title: Get It
permalink: /get_it/
comments: false
author_footer: false
---

## Distributions

WHDD is available in such Linux distributions:

* [SystemRescue](https://www.system-rescue.org) live system
* [ArchLinux AUR](https://repology.org/project/whdd/versions)
* [Gentoo](https://packages.gentoo.org/packages/sys-block/whdd)

## Latest revision from Git

To get the most recent revision of WHDD, you have to fetch it from git repository and compile:

~~~
git clone https://github.com/whdd/whdd
cd whdd
./build.sh
# Or ./build_static.sh if your system
# lacks libdialog or ncurses stuff
~~~
