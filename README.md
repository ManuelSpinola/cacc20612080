
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cacc20612080

<!-- badges: start -->
<!-- badges: end -->

The goal of cacc20612080 is to …

## Installation

You can install the development version of cacc20612080 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ManuelSpinola/cacc20612080")
```

## Example

This is a basic example which shows you how to use the package:

``` r
## basic example code
library(cacc20612080)
library(tidyverse)
library(sf)
library(stars)
```

``` r
ggplot() +
  geom_stars(data = ca_inm_cm4_8_ssp126_2061_2080[,,,1]) +
  scale_fill_viridis_c(name = "Annual Mean Temperature", option = "C", na.value = "transparent", direction = -1) +
  theme_minimal() +
  coord_equal()
```

<img src="man/figures/README-unnamed-chunk-2-1.png" width="100%" />
