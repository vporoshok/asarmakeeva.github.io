---
title: Changing midnight commander background color.
description: How to choose appropriate appearance of mc
date: 2019-10-08
categories:
- life
tags:
- mc
- midnight commander
cover:
    style: normal
---
I know sounds elementary, this is note more for myself not to forget about because every year I have a new Linux machine in a different country. Because I getting used to midnight commander (mc) as an addition for command line it is nice to have not eating your eyes blue background of mc.

So this is pretty easy:

* Open a terminal window, typing (not open mc, otherwise skin update doesn't apply).

```mcedit .config/mc/ini```

* Search for skin with F7 and change it. skin=modarin256 is really nice for example. 
* Save and restart terminal.

Look into ```/usr/share/mc/skins/``` to see the different themes.

Et voila! My mc looks like on pictire below:

{{< figure src="/post/pic/gray_background.png" width="800" height="800">}}