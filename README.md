# hwordcloud<img src="/assets/hwordcloud-fit.png" align="right" />
========================================================
[![](https://img.shields.io/badge/build-passing-brightgreen.svg?style=plastic)](https:www.czxa.top) [![](https://img.shields.io/badge/R-hwordcloud-brightgreen.svg?style=plastic)](https://www.czxa.top) [![](https://img.shields.io/badge/github-R-orange.svg?style=plastic)](https://www.czxa.top) [![](https://img.shields.io/badge/platform-Windows_OS|Mac_OS-orange.svg?style=plastic)](https://www.czxa.top)

## Introduction

The [htmlwidgets](https://github.com/ramnathv/htmlwidgets) package is very interesting and powerful. All the time, I want write my own html widgets, but I failed. This is my third try, finally I success! and the `hwordcloud` package come out. As I first try using `htmlwidgets`, I hope you will tolerate some of the flaws of this R package, and I will improve it in the future. Next, let's use `hwordcloud`!

## Installation:

I recommend downloading my packaged [hwordcloud_0.1.0.tar.gz](https://www.czxa.top/hwordcloud/hwordcloud_0.1.0.tar.gz) for offline installation.

```r
devtools::install_github('czxa/hwordcloud')
# or just use git
devtools::install_git("https://github.com/czxa/hwordcloud.git")
```

## Glimpse

![](https://czxb.github.io/br/hwordclud.png)

## vignettes

[使用R和HighCharts渲染词云图](https://czxb.github.io/br/hwordcloudc.html)

[Rendering word clouds using R + Highcharts](https://czxb.github.io/br/hwordcloud.html)

## PPT

[Rendering word clouds using R + Highcharts](https://czxb.github.io/br/hwordcloudppt.html)

## Licence

hwordclud has a dependency on Highcharts, a commercial JavaScript charting library. Highcharts offers both a commercial license as well as a free non-commercial license. Please review the licensing options and terms before using this software, as the hwordcloud license neither provides nor implies a license for Highcharts.

Highcharts (http://highcharts.com) is a Highsoft product which is not free for commercial and Governmental use.

## Acknowledgement

+ [jbkunst/highcharter](https://github.com/jbkunst/highcharter)
+ [Lchiffon/wordcloud2](https://github.com/Lchiffon/wordcloud2)

## Shiny Example

After Installation, you can run following codes to see hwordclud shiny app:

```r
dir <- system.file("examples", "hwordcloud", package = "hwordcloud")
setwd(dir)
shiny::shinyAppDir(".")
```

For Chinese:
```r
dir <- system.file("examples", "hwordcloudC", package = "hwordcloud")
setwd(dir)
shiny::shinyAppDir(".")
```

------------

<h4 align="center">

Code of Conduct

</h4>

<h6 align="center">

Please note that this project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md).<br>By participating in this project you
agree to abide by its terms.

</h6>

<h4 align="center">

License

</h4>

<h6 align="center">

MIT © czxa.top

</h6>
