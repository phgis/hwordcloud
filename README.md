# hwordcloud
<!-- badges: start -->
[![Travis build status](https://travis-ci.org/czxa/hwordcloud.svg?branch=master)](https://travis-ci.org/czxa/hwordcloud) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/hwordcloud?color=green)](https://cran.r-project.org/package=hwordcloud) ![](http://cranlogs.r-pkg.org/badges/grand-total/hwordcloud?color=green) ![](http://cranlogs.r-pkg.org/badges/hwordcloud?color=green) ![](http://cranlogs.r-pkg.org/badges/last-week/hwordcloud?color=green) [![Codecov test coverage](https://codecov.io/gh/czxa/hwordcloud/branch/master/graph/badge.svg)](https://codecov.io/gh/czxa/hwordcloud?branch=master) [![Launch binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/czxa/hwordcloud/master) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/czxa/hwordcloud?branch=master&svg=true)](https://ci.appveyor.com/project/czxa/hwordcloud) [![BioC status](http://www.bioconductor.org/shields/build/release/bioc/hwordcloud.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/hwordcloud)
<!-- badges: end -->

## Introduction

The [htmlwidgets](https://github.com/ramnathv/htmlwidgets) package is very interesting and powerful. All the time, I want write my own html widgets, but I failed. This is my third try, finally I success! and the `hwordcloud` package come out. As I first try using `htmlwidgets`, I hope you will tolerate some of the flaws of this R package, and I will improve it in the future. Next, let's use `hwordcloud`!

## Installation

```r
devtools::install_github('czxa/hwordcloud')
# or just use git
devtools::install_git("https://github.com/czxa/hwordcloud.git")
```

## vignettes

[Rendering word clouds using R + Highcharts](https://czxb.github.io/br/hwordcloud.html)

## Licence

hwordclud has a dependency on Highcharts, a commercial JavaScript charting library. Highcharts offers both a commercial license as well as a free non-commercial license. Please review the licensing options and terms before using this software, as the hwordcloud license neither provides nor implies a license for Highcharts.

Highcharts (http://highcharts.com) is a Highsoft product which is not free for commercial and Governmental use.

## Acknowledgements

+ [jbkunst/highcharter](https://github.com/jbkunst/highcharter)
+ [Lchiffon/wordcloud2](https://github.com/Lchiffon/wordcloud2)

## Shiny Example

After Installation, you can run following codes to see hwordclud shiny app:

```r
dir <- system.file("examples", "hwordcloud", package = "hwordcloud")
setwd(dir)
shiny::shinyAppDir(".")
```

------------

<h4 align="center">

License

</h4>

<h6 align="center">

MIT © czxa.top

</h6>
