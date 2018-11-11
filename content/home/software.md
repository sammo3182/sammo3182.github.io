+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = ""

# Order that this section will appear in.
weight = 6

+++

## `interplot`
Solt, Frederick, and **Yue Hu**. 2015. interplot: Plot the Coefficients of Variables in Interaction Terms. The Comprehensive R Archive Network (CRAN).

[![CRAN version](http://www.r-pkg.org/badges/version/interplot)](https://cran.r-project.org/web/packages/interplot/index.html) ![](http://cranlogs.r-pkg.org/badges/grand-total/interplot)![](http://cranlogs.r-pkg.org/badges/interplot?color=orange)

`interplot` is a tool for plotting the conditional coefficients ("marginal effects") of variables included in multiplicative interaction terms. The function plots the changes in the coefficient of one variable in a two-way interaction term conditional on the value of the other included variable. The resulting plot also includes simulated 95% confidential intervals of these coefficients.

To install:

* the latest released version: `install.packages("interplot")`.
* the latest development version: `devtools::install_github("sammo3182/interplot")`.

For more details, check out [the vignette](http://cran.r-project.org/web/packages/interplot/vignettes/interplot-vignette.html)
<br><br>

## `dotwhisker`
Solt, Frederick, and **Yue Hu**. 2015. dotwhisker: Dot-and-Whisker Plots of Regression Results. The Comprehensive R Archive Network (CRAN). 

[![CRAN version](http://www.r-pkg.org/badges/version/dotwhisker)](https://cran.r-project.org/web/packages/dotwhisker/index.html)![](http://cranlogs.r-pkg.org/badges/grand-total/dotwhisker)![](http://cranlogs.r-pkg.org/badges/dotwhisker?color=orange)

`dotwhisker` is an R package for quickly and easily generating dot-and-whisker plots of regression results, either directly from model objects or from tidy data frames. It provides a convenient way to create highly customizable plots for presenting and comparing statistics. It can be used to plot coefficients or other estimates (e.g., predicted probabilities) within a model or compare them across different models. The estimates are presented as dots with confidence interval whiskers.

To install:

* the latest released version: `install.packages("dotwhisker")`.
* the latest development version: `devtools::install_github("fsolt/dotwhisker")`.

For more details, check out [the vignette](https://cran.r-project.org/web/packages/dotwhisker/vignettes/dotwhisker-vignette.html)
<br><br>


## `pewdata`
Solt, Frederick, and **Yue Hu**. 2016. pewdata: Reproducible Retrieval of Pew Research Center Datasets. The Comprehensive R Archive Network (CRAN).

[![CRAN version](http://www.r-pkg.org/badges/version/pewdata)](https://cran.r-project.org/package=pewdata) 
![](http://cranlogs.r-pkg.org/badges/grand-total/pewdata) 
![](http://cranlogs.r-pkg.org/badges/pewdata?color=orange)
[![Travis-CI Build Status](https://travis-ci.org/fsolt/pewdata.svg?branch=master)](https://travis-ci.org/fsolt/pewdata)

`pewdata` is an R package that provides reproducible, programmatic access to survey datasets from the [Pew Research Center](http://www.pewresearch.org).

To install:

* the latest released version: `install.packages("pewdata")`
* the latest development version: 

```R
if (!require(ghit)) install.packages("ghit")
ghit::install_github("fsolt/pewdata")
```
Note that `pewdata` depends on the Firefox browser; if you don't already have it installed on your machine, [get it here](https://www.mozilla.org/firefox).

For more details, check out [the vignette](https://cran.r-project.org/web/packages/pewdata/vignettes/pewdata-vignette.html).