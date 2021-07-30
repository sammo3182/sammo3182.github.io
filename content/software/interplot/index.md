---
author: Fred Solt & HU Yue
title: interplot

categories:
- methodology
- visualization

date: "2021-12-01"
featured: true
draft: false

excerpt: A tool for plotting the conditional coefficients ("marginal effects") of variables included in multiplicative interaction terms. The function plots the changes in the coefficient of one variable in a two-way interaction term conditional on the value of the other included variable. The resulting plot also includes simulated 95% confidential intervals of these coefficients.
layout: single

links:
- icon: home
  icon_pack: fas
  name: website
  url: https://sammo3182.github.io/interplot/
- icon: github
  icon_pack: fab
  name: source
  url: https://github.com/sammo3182/interplot
---

<img src="featured-hex.png" width = "134.435" height = "155.25"  align="right" />

Solt, Frederick, and **Yue Hu**. 2015. interplot: Plot the Coefficients of Variables in Interaction Terms. The Comprehensive R Archive Network (CRAN).

[![CRAN version](http://www.r-pkg.org/badges/version/interplot)](https://cran.r-project.org/web/packages/interplot/index.html) ![](http://cranlogs.r-pkg.org/badges/grand-total/interplot)![](http://cranlogs.r-pkg.org/badges/interplot?color=orange)

`interplot` is a tool for plotting the conditional coefficients ("marginal effects") of variables included in multiplicative interaction terms. The function plots the changes in the coefficient of one variable in a two-way interaction term conditional on the value of the other included variable. The resulting plot also includes simulated 95% confidential intervals of these coefficients.

To install:

* the latest released version: `install.packages("interplot")`.
* the latest development version: `devtools::install_github("sammo3182/interplot")`.

For more details, check out [the vignette](http://cran.r-project.org/web/packages/interplot/vignettes/interplot-vignette.html)