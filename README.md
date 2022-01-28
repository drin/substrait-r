
<!-- README.md is generated from README.Rmd. Please edit that file -->

# substrait

<!-- badges: start -->

[![R-CMD-check](https://github.com/paleolimbot/substrait/workflows/R-CMD-check/badge.svg)](https://github.com/paleolimbot/substrait/actions)
<!-- badges: end -->

The goal of substrait is to provide an R interface to the
[Substrait](https://substrait.io) cross-language serialization for
relational algebra.

## Installation

You can install the development version of substrait from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("paleolimbot/substrait")
```

You will need the [protocol
buffers](https://developers.google.com/protocol-buffers) development
files installed. You can do this on MacOS using `brew install protobuf`,
on Debian/Ubuntu using `apt-get install libprotobuf-dev`, and on Red
Hat/Fedora by installing `protobuf-devel`.

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(substrait)
## basic example code
```