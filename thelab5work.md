my lab 5 work
================
Damien MacFarland
11/06/2021

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](thelab5work_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

``` r
evals.scores <- evals %>%
  select(score, bty_avg)
evals.scores
```

    ## # A tibble: 463 x 2
    ##    score bty_avg
    ##    <dbl>   <dbl>
    ##  1   4.7    5   
    ##  2   4.1    5   
    ##  3   3.9    5   
    ##  4   4.8    5   
    ##  5   4.6    3   
    ##  6   4.3    3   
    ##  7   2.8    3   
    ##  8   4.1    3.33
    ##  9   3.4    3.33
    ## 10   4.5    3.17
    ## # ... with 453 more rows
