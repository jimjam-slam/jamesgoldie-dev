---
title: Sverto
work-type: package
categories: [rstats, package, quarto, pandoc, svelte]
date: 2023-02-15
description: Use Svelte components in your Quarto documents, and have them seamlessly react to Observable JS, making it quick and easy to build bespoke visuals that animate in response to user inputs or other changing data in your document.
---

[Find this on sverto.jamesgoldie.dev](https://sverto.jamesgoldie.dev){.btn .btn-gradient}

Quarto helps users build beautiful documents regardless of their language of choice, and it encourages data analysts and scientists to explore web visualisation by making JavaScript accessible and easy to use. It makes interactive visualisations intuitive to write, but animated visuals are still a challenge that require either dipping into a high-level JavaScript library or learning a lower-level one like d3.

Svelte is a framework for building web visualisations and apps in JavaScript. Svelte goes out of its way to make writing self-contained components, like charts, comfortable and intuitive. It has a great playground environment for developing and testing components, but like many web frameworks, the experience is much more complex when you start developing locally.

**Sverto aims to make it as easy to use animated Svelte charts in Quarto documents as it is to work on them in the Svelte REPL: just write a `.svelte` file, add it to a Quarto document, and Sverto should take care of the rest.**
