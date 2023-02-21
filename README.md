
# prsr

<!-- badges: start -->
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/mglev1n/prsr/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/mglev1n/prsr/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of prsr is to provide a set of convenience functions relevant for calculating polygenic risk scores on a target dataset. The package uses plink2 to calculate polygenic risk scores (PRS) on a target dataset given a base dataset that includes variants, effect alleles, and corresponding weights.

## Installation

You can install the development version of prsr from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("mglev1n/prsr")
```

