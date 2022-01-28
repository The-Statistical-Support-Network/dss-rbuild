---
title: "Package Development in R for Predator Free New Zealand 2050"
author: "Anthony Davidson"
date: "January 2022"
description: "This guide walks through the process of developing an R package"
site: "bookdown::bookdown_site"
documentclass: book
geometry: "margin=1.5in"
biblio-style: apalike
link-citations: yes
---

# Introduction {-}

I have taken the guide generated at [https://iqss.github.io/dss-rbuild/](https://iqss.github.io/dss-rbuild/) for my PhD work and future package development.

## Table of Contents {-}

This guide is organized into three parts.

1. First, we'll run through [The proper way to structure and test packages](./package-development.html).

2. Second, we'll discuss [Version Control with Git and GitHub](./version-control.html)

3. Lastly, we'll [briefly look at a couple of IDEs](./integrated-development-environments.html), which are just pieces of software that make it easier to write packages.

[Here's a link to a great devtools cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/03/devtools-cheatsheet.pdf) which puts most of the useful commands in this guide in one place.


NOTE 2022: I hope to do this for PFNZ 2050 too

We also wrote a small development example package (called `devex`) which you can find linked [here, on GitHub](https://github.com/IQSS/dss-rbuild/tree/master/devex). If you haven't used GitHub yet, don't worry - we'll go over how to use GitHub later.

Also, this guide is still under development, and we take feedback! If you find anything confusing or think the guide misses important content, please email `help@iq.harvard.edu`

NOTE 2022: I have taken the original guide with the key contributors below and developed some extra code and other resources I have used for my PhD work. Maybe some of it will be helpful in the future? :)

## Authors and Sources {-}

It's worth acknowledging a few people who helped make this guide possible. First of all, Simo Goshev and Steve Worthington at Harvard's IQSS helped design the structure of the guide and edited the content. Second, Asher Spector at Harvard College did the hard work of actually writing the tutorial in Rmarkdown and configuring the GitHub repo and website. Third, Jinjie Liu at IQSS helped to polish the content. Fourth, this guide was written for a different audience, but a lot of its structure and content is based on Hadley Wickham's book [R Packages](http://r-pkgs.had.co.nz/). To help write the sections on testing, we also referenced [Christopher Gandrud's 'Failing Faster' Presentation](
http://slides.com/christophergandrud/failing-faster#/24), and [Christopher Gandrud's Broader Testing Guidelines](https://github.com/IQSS/social_science_software_toolkit/blob/master/testing/recommended_testing_tools_R.md#recommended-testing-tools-and-process-for-r-packages). For the section on on Version Control, we referenced [Karl Broman's Book](https://kbroman.org/github_tutorial/), a [Git-Tower post](https://www.git-tower.com/learn/git/faq/restore-repo-to-previous-revision
), and the GitHub documentation [here](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics) and  [here](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) to help write this guide.
