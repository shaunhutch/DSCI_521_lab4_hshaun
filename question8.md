question7
================
Shaun Hutchinson
2022-09-26

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](question8_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

#### New Code Chunk 1

The code chunk below combines three values together in a list.

``` r
x <- 1
y <- 3
z <- -25
answer <- c(x, y, z)
answer
```

    ## [1]   1   3 -25

#### New Code Chunk 2

This code chunk takes the average from the list in code chunk 1

``` r
library(tidyr)
avg_answer <- sum(answer)/length(answer)
avg_answer
```

    ## [1] -7
