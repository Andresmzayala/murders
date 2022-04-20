Report on Gun Murders
================
Julian Ayala
19/04/2022

## Introduction

This is a report on 2010 gun murder rates obtain from FBI reports. The
original data was obtained from [this Wikipedia
page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state).

We are going to use the following library:

``` r
library(tidyverse)
```

and load data we already wrangled:

``` r
load("rda/murders.rda")
```

## Murder rate by state

We note the large state to state variability by generating a barplot
showing the murder rate by state:

![](Report-on-Gun-Murders_files/figure-gfm/murder-rate-by-state-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot. Note that
‘message=FALSE’ was added to prevent printing the package downloading
result.
