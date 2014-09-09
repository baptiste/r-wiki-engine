
# R Wiki Engine - Under Development

The goal is to have wikis that are developed on Github,
hosted on Github Pages, and written in Markdown. They must be
able to nicely highlight and run R code.

## Implementation

* This repository contains the wiki engine and an
  example wiki as well.
* The wiki itself is in a github repository.
* The web rendering of it is on Github Pages.
* We use Travis to automatically rebuild the modified
  wiki page(s). Travis runs R (Rmarkdown or knitr),
  possibly Jekyll as well, and deploys the result to
  Github Pages.

## Implementation challenges

Being a static website, it is unlikely that this setup will
ever be as smooth as a proper Wiki. In particular, here are
some features that are challenging to implement:

* Tags.
* Search. Probably possible to include a static search engine,
  that is included in the we site. If the wiki gets too big,
  then an external search engine or Google Custom Search can
  be used.
