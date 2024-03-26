---
title: Is It Hot Right Now?
categories: [js, rstats, python, quarto, ojs, webapp, climatechange, weather, dataviz]
date: 2024-02-08
description: Is it really hot today, or does it just feel that way?
image: isithotrightnow.png
twitter-card:
  image: isithotrightnow.png
---

[Find this at isithotrightnow.com](https://isithotrightnow.com){.btn .btn-gradient}

Sometimes you just need a simple answer to a (not-so-)simple question: is it hot right wow?

Mat Lipson, Stefan Contractor and I cobbled the basic concept for this over a few weekends in late 2017. After running for seven years, we decided to give it a major rework, expanding from 9 stations across Australia to over 50, adding an interactive map and a search function, as well as improving the graphics.

The backend was also completely rebuilt and shifted to AWS Lambda to make it cheaper, more scalable and better documented.

[![Map of Australian weather stations on "Is it Hot Right Now?"](iihrn-map.png)](https://isithotrightnow.com)
