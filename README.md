
<!-- README.md is generated from README.Rmd. Please edit that file -->

# BCyto <img src="inst/logo/LogoHRes.png" align="right" alt="" width="160"/>

<!-- badges: start -->
<!-- badges: end -->

**BCyto** is is an open-source project that provides an user-friendly,
high-performance interface for Flow Cytometry analysis.

## Installation

**BCyto** can be installed by first installing R and typing the
following commands in R console:

``` r
#to allow installation of GitHub packages
install.packages("devtools")
#to enable donwload of BioConductor dependencies
install.packages("BiocManager")
#BCyto can then be installed
devtools::install_github("BonilhaCaio/BCyto")
```

*Note: as Bioconductor currently does not support the Apple M1 (a.k.a.
arm64) architecture in native mode, BCyto requires the Intel 64-bit R
version (x86_64 arch) to work in Apple M1 computers. As such, when
downloading R from CRAN, please choose R-x.x.x.pkg, and not
R-x.x.x-arm64.pkg.*

## Usage

**BCyto** Shiny-based user interface with all its tools is generated
through the package’s single function:

``` r
BCyto::runBCyto()
```

## Credits and citation

A publication where dependencies and imports will be appropriately
credited is on the way. Meanwhile, please cite **BCyto** as follows:

``` r
citation("BCyto")
#> 
#> To cite BCyto in publications use:
#> 
#>   Caio Santos Bonilha (2021). BCyto: A Shiny App for Flow Cytometry
#>   Data Analysis and Visualization. R package version 1.0.0.
#>   https://github.com/BonilhaCaio/BCyto.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {BCyto: A Shiny App for Flow Cytometry Data Analysis and Visualization},
#>     author = {Caio Santos Bonilha},
#>     year = {2021},
#>     note = {R package version 1.0.0},
#>     url = {https://github.com/BonilhaCaio/BCyto},
#>   }
```
