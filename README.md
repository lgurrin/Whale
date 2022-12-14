
<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

[![Codecov test
coverage](https://codecov.io/gh/lgurrin/Whale/branch/main/graph/badge.svg)](https://app.codecov.io/gh/lgurrin/Whale?branch=main)

[![R-CMD-check](https://github.com/lgurrin/Whale/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/lgurrin/Whale/actions/workflows/R-CMD-check.yaml)

<!-- badges: end -->

# Whale

Whale-come! This R package was inspired by
[cowsay](https://github.com/sckott/cowsay) and
[praise](https://github.com/rladies/praise). I hope this package made
you smile today!

## First things first

`Whale` is a toy project and is still under development. You can install
the latest version from [GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("fontikar/ohwhaley")
remotes::install_github("lgurrin/Whale")
```

## Take it for a spin

`Whale` contains one function only. `say()` will echo a randomly chosen
whale-themed phrase for your enjoyment.

``` r
library(Whale)
 
say() 
#> 
#>             ------ 
#>            Get whale soon! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```

Alternatively, you can supply your own phrase

``` r
say("I'm beached as bro!!!")
#> 
#>             ------ 
#>            I'm beached as bro!!! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```
