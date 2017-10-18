---
title: "Nsamba_review.Rmd." https://github.com/btrampe/EEOB_R_Assignment
author: "ensamba"
date: "10/17/2017"
output: html_document

#     Markdown files

The author did a great job desribing the steps he used to work through the assignment from downloading the files from internet through processing them to address the questions. His entire workflow is very easy to follow and the Markdown file well written.

##    Data inspection

The author exploited all the functions learnt in class to inspect his data and very well described it.



###   File formatting, data processing and outputs

The file outputs for the `Maize` and `Teosinte` IDs are not accurate on all chromosomes with SNPs based on increasing and decreasing SNP position values. I tried clicking on all of them and only the header showed up except *teosinte_Chr_1_Decreasing* text file.
`I tried running the code that produced the files and it seemed working fine`. I don't know exactly what went wrong. The author would instead check all his output files before committing them to ensure that they are accurate.
I am thinking that perhaps improper files were named correct and proper files incorrect and that at the time of staging and commiting, incorrect files were uploaded. This because on the directory, on a master branch, there is a commit for correct files which I think instead incorrect ones were staged.

####  File Organization and storage
Also the text files formats could be somewhat improved for visualization and trackable. The question asked to group the files based on increasing and decreasing SNP position values thus separate folders for each of the outputs would make the work more neat. I would create folders for maize and Teosinte and in each subfolders to keep text files based on increasing and decreasing SNP position values.  

##### Part II
I didnot see graphs for this section although the codes were written and icluded in the `Markdown` file Maybe the author forgot to commit them, I guess.
Again, careful verification of the staged files for commiting were very much needed.

#In General,
The codes were very robust but the author didnot take time to check his file before commiting them to his repository.
Also the files could be properly organized morethan he did.
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
