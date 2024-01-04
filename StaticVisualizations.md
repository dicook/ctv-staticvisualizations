---
name: StaticVisualizations
topic: Static Graphics
maintainer: Dianne Cook, Sherry Zhang
email: dicook@monash.edu
version: 2023-02-23
source: https://github.com/cran-task-views/StaticVisualizations/
---

One of the strengths of R is the wealth of data plotting packages. This CRAN Task View maintains a list of static graphics packages, and links to web resources on plotting data.

Note that some of these packages are on CRAN and others are on GitHub, Bioconductor, or R-Forge.

If you think that a package is missing from this list, please let us know through issues or pull requests in the [GitHub repository](https://github.com/cran-task-views/VisualizationStatic).

## Table of contents

- [Design systems](#design)
- [Grouping of plots](#grouping)
- [Themes to styling displays](#theming)
- [Add-ons to lattice](#lattice)
- [Add-ons to ggplot2](#ggplot2)
- [Miscellaneous](#miscellaneous)
- [Graphics resources and advice web sites](#advice)

## [Design systems]{#design}

- `r package("graphics")` (base) | The original graphics engine.
- `r package("grid")` | Implements the primitive graphical functions.
- `r package("gridGraphics")` | Redraw Base Graphics Using 'grid' Graphics.
- `r package("ggplot2")` | Create elegant data visualisations using the grammar of graphics. Built on the `grid` system.
- `r package("lattice")` | Create data visualisations using the trellis method. Built on the `grid` system.

## [Grouping of plots]{#grouping}

- `r package("cowplot")` | Streamlined plot theme and plot annotations for `ggplot2`
- `r package("gridExtra")`
- `r package("patchwork")`
- `r package("ggpubr")`
- `r package("gtable")`

## [Themes to styling displays]{#theming}

- `r package("basetheme")` | Themes for base graphics plots.
- `r package("ggthemes")` | Extra themes, scales and geoms for `r package("ggplot2")`.
- `r package("thematic")` | Unified and automatic theming of `r package("ggplot2")`, `r package("lattice")`, and `r package("base")` R Graphics
- `r package("tvthemes")` | TV show themes and color palettes for `r package("ggplot2")` graphics

## [Add-ons to lattice]{#lattice}

- `r package("latticeExtra")` | Extra graphical utilities based on lattice.
- `r package("adegraphics")` | Lattice-based package for the representation of multivariate data.
- `r package("loa")` | Lattice options and add-ons.
- `r package("stripless")` | Structured trellis displays without strips for lattice graphics.
- `r package("tactile")` | New and extended plots, methods, and panel functions for `r package("lattice")`

## [Add-ons to ggplot2]{#ggplot2}

An extensive list with more than 100 add-ons for `r package("ggplot2")` is avilable at [the gallery of ggplot2 extensions](https://exts.ggplot2.tidyverse.org/gallery/). (We point to this rather than duplicate efforts.)

## [Miscellaneous]{#miscellaneous}

`r package("vdiffr")` | Visual regression testing and graphical diffing with testthat

## [Graphics resources and advice web sites]{#advice}

- [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org)
- [Data Visualization: A practical introduction](https://socviz.co)
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/)
- [Graphical Data Analysis with R](http://www.gradaanwr.net)
- [The R Graph Gallery](https://www.r-graph-gallery.com)
