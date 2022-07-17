---
title: ggflags
categories: [rstats, package]
date: 2017-09-29
project-date: Sep 2017
description: A package for plotting country flags as bubbles or balloons in ggplot.
---

[Find this on github.com](https://github.com/jimjam-slam/ggflags){.btn .btn-gradient}

I've taken over development of ggflags, an extension to ggplot2 that allows you to plot country flags as points or bubbles. The original was developed by  [Baptiste's Auguié](https://github.com/baptiste/ggflags), and I've so far extended it to use round, vector flags from the [EmojiOne v2](https://www.emojione.com/) set (so they'll look great at any size).

We're currently working on SVG export for interactive graphics. It works with `ggsave` if you have the `svglite` package installed, although you lose the structure of the plot, which isn't great for interactive applications. `gridSVG::grid.export` also works, although you'll have to do some manual tweaking of the output to correct for a bug with the viewport.

If you think you can help me work out these issues, or think the package could do other things, feel free to [open an issue](https://github.com/rensa/ggflags/issues) or [open a pull request](https://github.com/rensa/ggflags/pulls)!

[![The `{ggflags}` package](ggflags.png)](https://github.com/jimjam-slam/ggflags)