---
knit: "bookdown::render_book"
title: "sits book"
author: ["Author1", "Author2", "Author3", "Author4"]
date: "2020-11-08"
site: bookdown::bookdown_site
documentclass: book
github-repo: e-sensing/sits-book
fig_caption: yes
header-includes:
- \usepackage{float}
- \usepackage{xcolor}
- \floatsetup[table]{capposition=bot}
bibliography:
- book.bib
- packages.bib
biblio-style: apalike
link-citations: yes
description: This is a minimal example of using the bookdown package to write a book.
  The output format for this example is bookdown::gitbook.
---

# Prerequisites

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$.

The **bookdown** package can be installed from CRAN or Github:


```r
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```

Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.org/tinytex/>.


