---
title: unswthesisdown
description: A package for writing your thesis in RMarkdown according to UNSW guidelines.
categories: [rstats, package]
date: 2017-07-09
image: thesis.png
twitter-card:
  image: thesis.png
aliases:
  - ../../unswthesisdown/index.html
---

_**Note:** the RMarkdown publishing landscape has moved on considerably since I wrote my thesis with `underthesisdown`. I have some, uh, **strong** opinions about LaTeX, and I'd be more inclined to use Paged CSS and [`pagedown`](https://pagedown.rbind.io) to write a long report or thesis these days. I belive [Quarto](https://quarto.org) has plans for a Paged CSS solution too!_

[Find this on github.com](https://github.com/jimjam-slam/unswthesisdown){.btn .btn-gradient}

[Chester Ismay's](http://twitter.com/old_man_chester) lovely [`thesisdown`](https://github.com/ismayc/thesisdown) package allows people to ditch LaTeX and write their thesis in RMarkdown. RMarkdown allows you to insert blocks of R code into your manuscript, but even if you don't want to actually do analysis in your manuscript, you can use RMarkdown to easily insert tables and figures, or you can just write plain Markdown.

Frankly, either option beats out ugly LaTeX, and this package pipes your readable RMarkdown through a LaTeX template so that you get that pristine TeX look without actually having to write it. Plus, you can produce a gorgeous [gitbook](https://www.gitbook.com/) version to host on the web!

I forked `ismayc/thesisdown` because the original is built with Reed College in mind. The [`unswthesisdown` fork](https://github.com/rensa/unswthesisdown) modifies the LaTeX template to be suitable for UNSW students. That mostly means it uses A4 paper with UNSW margins instead of letter size, but it also adds a prettier title page and hyperlinks. Frankly, you could probably use it for any Australian university unless they have different margin sizes (and you can tweak those in the LaTeX template if you need to).

As always, I'm happy to take feedback and changes to improve the template, either via [GitHub](http://github.com/rensa/unswthesisdown) issues and PRs or by [getting in touch](http://twitter.com/rensa_co).