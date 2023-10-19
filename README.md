
<!-- README.md is generated from README.Rmd. Please edit that file -->

# MARS <img src="man/figures/README-hex.png" style="float:right; height=139px;" />

> Multi-stock assessment with RTMB

<!-- badges: start -->

[![R-CMD-check](https://github.com/Blue-Matter/MSA/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/Blue-Matter/MSA/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

MARS (**Multi-stock Assessment with Regional Spatiotemporal dynamics**)
is a multi-stock, spatially-explicit age-structured model. It is
intended for use in fisheries where stock composition can not be readily
identified in fishery data.

Funding for development of MARS is provided by the NOAA Fisheries
Bluefin Tuna Research Program
([BTRP](https://www.fisheries.noaa.gov/grant/bluefin-tuna-research-program)
Grant NA23NMF4720184) in collaboration with the Ocean Foundation.

Atlantic bluefin tuna (*Thunnus thynnus*) is the first intended case
study.

## Installation

You can install the R package from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("Blue-Matter/MARS")
```