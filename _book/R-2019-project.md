--- 
site: bookdown::bookdown_site
title: "The Title of The Project"
subtitle: "Course R-2019 Project"
author: Autror 1, Author 2
date: "2019-10-21"
description: "..."
---

# Summary {-}

... 

<!-- This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$. -->

<!-- The **bookdown** package can be installed from CRAN or Github: -->

<!-- ```{r eval=FALSE} -->
<!-- install.packages("bookdown") -->
<!-- # or the development version -->
<!-- # devtools::install_github("rstudio/bookdown") -->
<!-- ``` -->

<!-- Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`. -->

<!-- To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.name/tinytex/>. -->

<!-- ```{r include=FALSE} -->
<!-- # automatically create a bib database for R packages -->
<!-- knitr::write_bib(c( -->
<!--   .packages(), 'bookdown', 'knitr', 'rmarkdown' -->
<!-- ), 'packages.bib') -->
<!-- ``` -->

<!--chapter:end:index.Rmd-->

# Introduction {#intro}


## Background 

Background information and short introduction^[Approx. 2-5 sentences] why this study (analysis) is needed.



## The purpose and the tasks

The purpose of this analysis:

The tasks:









<!-- ------------------- -->

<!-- You can label chapter and section titles using `{#label}` after them, e.g., we can reference Chapter \@ref(intro). If you do not manually label them, there will be automatic labels anyway, e.g., Chapter \@ref(methods). -->

<!-- Figures and tables with captions will be placed in `figure` and `table` environments, respectively. -->

<!-- ```{r nice-fig, fig.cap='Here is a nice figure!', out.width='80%', fig.asp=.75, fig.align='center'} -->
<!-- par(mar = c(4, 4, .1, .1)) -->
<!-- plot(pressure, type = 'b', pch = 19) -->
<!-- ``` -->

<!-- Reference a figure by its code chunk label with the `fig:` prefix, e.g., see Figure \@ref(fig:nice-fig). Similarly, you can reference tables generated from `knitr::kable()`, e.g., see Table \@ref(tab:nice-tab). -->

<!-- ```{r nice-tab, tidy=FALSE} -->
<!-- knitr::kable( -->
<!--   head(iris, 20), caption = 'Here is a nice table!', -->
<!--   booktabs = TRUE -->
<!-- ) -->
<!-- ``` -->

<!-- You can write citations, too. For example, we are using the **bookdown** package [@R-bookdown] in this sample book, which was built on top of R Markdown and **knitr** [@xie2015]. -->

<!--chapter:end:01-intro.Rmd-->

# Data {\*part}

# Raw data {#raw-data}


## The source of data

...

## Description of raw data

The desctiption or raw data:

- Equipment used to collect it
- References


## Codebook of raw data

<!--chapter:end:02-raw-data.Rmd-->

# Pre-processing {#main-preprocessing}

The methods and R codes to transforma data from the raw to tidy analysis-friendly form.

The final result of preprocessing must comply the Tidyverse style guide 
(especially the variable names; pay attention that there are no guidelines 
for variable values).

<!--chapter:end:03-main-preprocessing.Rmd-->

# Pre-processed (Tidy) Data

## Overview of data structure

...

## Codebook {#codebook-preprocessed}

...

<!--chapter:end:04-tidy-data.Rmd-->

# Final Words

We have finished a nice book.

<!--chapter:end:05-summary.Rmd-->


# References {-}


<!--chapter:end:06-references.Rmd-->

--- 
title: "The Title of The Project"
subtitle: "Course R-2019 Project"
author: Autror 1, Author 2
date: "2019-10-21"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "..."
---

# Summary {-}

Placeholder



<!--chapter:end:index.Rmd-->


# Introduction {#intro}

Placeholder


## Background 
## The purpose and the tasks

<!--chapter:end:01-intro.Rmd-->

# Data {\*part}

# Raw data {#raw-data}


## The source of data

...

## Description of raw data

The desctiption or raw data:

- Equipment used to collect it
- References


## Codebook of raw data

<!--chapter:end:02-raw-data.Rmd-->

# Pre-processing {#main-preprocessing}

The methods and R codes to transforma data from the raw to tidy analysis-friendly form.

The final result of preprocessing must comply the Tidyverse style guide 
(especially the variable names; pay attention that there are no guidelines 
for variable values).

<!--chapter:end:03-main-preprocessing.Rmd-->

# Pre-processed (Tidy) Data

## Overview of data structure

...

## Codebook {#codebook-preprocessed}

...

<!--chapter:end:04-tidy-data.Rmd-->

# Final Words

We have finished a nice book.

<!--chapter:end:05-summary.Rmd-->


# References {-}


<!--chapter:end:06-references.Rmd-->


<!--chapter:end:R-2019-project.Rmd-->

