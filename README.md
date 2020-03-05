An introduction to network analysis and inference
================

> This repository regroups the material (slides, labs) associated to the
> course about “graph analysis and inference”, given on various
> occasionsat Imperial College.

## Slides

  - **Statistics on network data, Graph Partitionning, Clustering** -
    [slides](https://github.com/jchiquet/CourseNetworkLondon/raw/master/slides/DescriptiveAnalysis/DescriptiveAnalysis.pdf)
  - **Network Inference with sparse Graphical Models** -
    [slides](https://github.com/jchiquet/CourseNetworkLondon/raw/master/slides/NetworkInference/NetworkInference.pdf)

## Labs

**sheets**
[PDF](https://github.com/jchiquet/CourseNetworkLondon/raw/master/labs/labs.pdf),
[HTML](https://github.com/jchiquet/CourseNetworkLondon/raw/master/labs/labs.html)
(download the raw HTML and reopen it from your favorite browser).

-----

You need to have a recent version of
[Rstudio](https://www.rstudio.com/products/rstudio/download/) installed
with [R](https://cran.r-project.org) \>= 3.5.1 and the following
packages installed:

### Basic packages for R extensions

``` r
install.packages("devtools")
install.packages("knitr")
install.packages("rmarkdown")
```

### Packages for graph manipulation

``` r
install.packages("igraph")
```

### Packages for stochastic block models

``` r
install.packages("blockmodels")
```

### Packages for network inference

``` r
install.packages("simone")
install.packages("QUIC")
install.packages("huge")
install.packages("stabs")
```

### Packages for fancy plotting

``` r
install.packages("tidyverse")
install.packages("corrplot")
install.packages("ggraph")
```

## References

  - [Rstudio cheat
    sheets](https://www.rstudio.com/resources/cheatsheets/)

Some books

  - [Statistical Analysis of Network Data: Methods and Models, by Eric
    D.
    Kolaczyk](https://books.google.fr/books?id=Q-GNLsqq7QwC&source=gbs_book_similarbooks)
  - [Statistical Analysis of Network Data with R, by Eric D. Kolaczyk,
    Gábor
    Csárdi](https://books.google.fr/books?id=cNMhBAAAQBAJ&source=gbs_navlinks_s)
  - [Friedman, Jerome, Trevor Hastie, and Robert Tibshirani. The
    elements of statistical learning. Vol. 1. No. 10. New York, NY,
    USA:: Springer series in
    statistics, 2001.](https://web.stanford.edu/~hastie/ElemStatLearn/)
  - Bishop, C. (2000). Introduction to graphical modelling, 2nd edn.
    Springer, New York.
  - Højsgaard, S., Edwards , D., Lauritzen, S. (2012). Graphical Models
    with R. Springer, New York.
