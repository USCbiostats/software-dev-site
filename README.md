
# software-dev-site

<!-- badges: start -->
<!-- badges: end -->

The goal of software-dev-site is to provide a website to store the information located in the wiki of the [software-dev](https://github.com/USCbiostats/software-dev) repository.

The website is built as a [rmarkdown website](https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html). The websites structure is defined in the `_site.yml` file. And the whole website is built by running `rmarkdown::render_site()`.

This page is not setup to be rendered online, so rendering should be done locally with `rmarkdown::render_site()` and all changes should be pushed.
