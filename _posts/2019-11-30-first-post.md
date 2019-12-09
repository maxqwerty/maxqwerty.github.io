---
title: How this site was made
author: Maxim Rybas
layout: post
---

Project [GitHub Pages](https://pages.github.com/){:target="_blank"} is based on [Jekyll](https://jekyllrb.com/){:target="_blank"} framework. It was written with Ruby and provides templates ([themes](https://jamstackthemes.dev/ssg/jekyll/){:target="_blank"}), so I just looked around and find this one: [Prologue](https://chrisbobbe.github.io/jekyll-theme-prologue/){:target="_blank"} by [Chris Bobbe](https://chrisbobbe.github.io/){:target="_blank"}.

It is eay: download code, customize some links with configuration file, add some pictures and voilà: site for portfoio is done!

* For magnificent constellations at the front page were used [Particles JS](https://vincentgarreau.com/particles.js/){:target="_blank"} and HTML tag `<meta name="viewport">` to correct scaling on mobile devices.
* For blog page about [Programming Languages Statistics](/2019/12/08/lang-stats.html) was used HTML tag `<embed>` and command <br>`jupyter-nbconverter --to html Statistics.ipynb` <br>to generate static HTML page rendered from Jupyter Notebook.

* Favicon is ironical Negative Space of CatoLamp (Котолампа), as well as my avatar on [GitHub](https://github.com/maxqwerty){:target="_blank"}.