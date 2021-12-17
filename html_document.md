---
title: "Module 3 HTML Document"
author: "Elhami A.A. Ahmed"
date: "12/17/2021"
output: 
    html_document:
      keep_md: true 
      fig_width: 6
      fig_height: 6
      toc: yes
      toc_float: TRUE
      code_folding: hide
---



# Module 3 HTMl Document
## R Markdown {#nextsteps .emphasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

### Plot of the Cars dataset


```r
plot(cars)
```

![](html_document_files/figure-html/cars-1.png)<!-- -->

## Including Plots

You can also embed plots, for example:

### Plot of the Pressure dataset

![](html_document_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## A short list

* apples
* oranges
* lemon

## A simple math equation

$$ Y = \beta_0 + \beta_1*x $$
