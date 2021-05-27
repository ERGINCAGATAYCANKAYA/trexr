
<!-- README.md is generated from README.Rmd. Please edit that file -->

# trexr <img src="inst/app/www/hex-trexr.png" width=130 height = 150 align="right" />

The goal of trexr is to explore trees in R visually and graphically.
This package is *less* research based and more application based. Thus,
if you are looking for more details on LiDAR and tree segmentation
please see
[weblidar-treetop](https://github.com/carlos-alberto-silva/weblidar-treetop)
excellent app (a lot of the inspiration for this app was from
[weblidar-treetop](https://github.com/carlos-alberto-silva/weblidar-treetop)).
This package allows the user to do explore canopy height models (CHM)
through graphs (histograms, density, boxplot), map (leaflet), 3-d and
stats. The main feature is the ability to crop your input (AOI) and
generate new information. In addition, users can convert from meters to
feet (vice-versa) or change height (filter) CHM on the fly.

## Installation

And the development version from
[GitHub](https://github.com/USFSr1GeospatialGroup/trexr) with:

``` r
# install.packages("devtools")
devtools::install_github("USFSr1GeospatialGroup/trexr")
```

## Example

Below is an example of using the app.

``` r
library(trexr)
run_app()
```

## Video

<video width="320" height="240" controls>
<source src="inst/app/www/trexr_vid.mp4" type="video/mp4">
</video>
