# Kate Hertweck's website and blog

This repository contains the code used to build and deploy my website and blog.

## Tools 

- built in [RStudio](https://rstudio.com) using the R package [`blogdown`](https://bookdown.org/yihui/blogdown/)
- `blogdown` generates sites using [Hugo](https://gohugo.io);
the template used here is [soho](https://themes.gohugo.io/soho/)
- the site is deployed using [Netlify](https://www.netlify.com),
which is the preferred method mentioned in the [`blogdown` book](https://bookdown.org/yihui/blogdown/)

## Usage

- install and load `blogdown` (available through CRAN)
- preview the website locally using `blogdown::serve_site()`; 
this autoupdates as changes are saved
- to stop server, use `servr::daemon_stop(1)`
- for more information, see the [`blogdown` documentation](https://github.com/rstudio/blogdown)
