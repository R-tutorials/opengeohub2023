# OpenGeoHub Summer School 2023

This repo contains code to support my contribution to the OpenGeoHub
Summer School 2023.

## Tidy geographic data with sf, dplyr, ggplot2, geos and friends

### Abstract

This lecture will provide an introduction to working with geographic
data using R in a ‘tidy’ way. It will focus on using the `sf` package to
read, write, manipulate, and plot geographic data in combination with
the `tidyverse` metapackage. Why use the `sf` package with the
`tidyverse`? The lecture will outline some of the ideas underlying the
`tidyverse` and how they can speed-up data analysis pipelines, while
making data analysis code easier to read and write. We will see how the
following lines

``` r
library(sf)
library(tidyverse)
```

can provide a foundation on which the many geographic data analysis
problems can be solved. The lecture will also cover on more recently
developed packages that integrate with the `tidyverse` to a greater and
lesser extent. We will look at how the `geos` package, which provides a
simple and high-performance interface to the GEOS library for performing
geometric operations on geographic data, integrates with the
`tidyverse`. The `tidyverse` is not the right tool for every data
analysis task and we touch on alternatives for working with raster data,
with reference to the `terra` package, and alternative frameworks such
as `data.table`. Finally, we will also look at how the ‘tidy’ philosophy
could be implemented in other programming languages, such as Python.

The focus throughout will be on practical skills and using packages
effectively within the wider context of project management tools,
integrated development environments (we recommend VS Code with
appropriate extensions or RStudio), and version control systems.

## Processing large OpenStreetMap datasets for geocomputational research

TBC

## Using geocomputation in government

TBC
