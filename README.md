# Workshop materials for *Collaborative Coding for Scientific Research: Git, GitHub, and open science*

This (will be) course materials for a workshop to be held at Michigan State University, sponsored by the MSU Institute for Biodiversity, Ecology, Evolution, and Macrosystems (<https://ibeem.msu.edu>)

### About

These are the source files for the materials, to see the materials, go to the rendered book on github pages (URL pending).

### Development

The book is coded based on R Markdown and **bookdown** (<https://github.com/rstudio/bookdown>). For more about `bookdown` package, see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at <https://bookdown.org/yihui/bookdown/> 

To install the packages needed, use [renv](https://rstudio.github.io/renv/articles/renv.html)

After cloning/downloading these files, in R use

``` r
install.packages('renv')
renv::init()
```

To preview the web-version of book use

``` r
bookdown::serve_book()
```

You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions for using bookdown are in the bookdown book <https://bookdown.org/yihui/bookdown/build-the-book.html>.

---

<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>
