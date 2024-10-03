---
title: Brighton and Hove Secondary School Admissions
author: Adam Dennett
date: '2024-10-03'
slug: []
categories: []
tags: []
subtitle: ''
excerpt: ''
draft: yes
series: ~
layout: single
---

Here I'm going to write a few thoughts and observations about the newly proposed Brighton and Hove Secondary School Admissions Policy and proposed changes to the school catchment areas.

I'm going to do the best I can with the data and information available, but as I see it, there are issues with various elements of the different proposal options - to a greater or lesser degree.

All current information is available from here:

<https://yourvoice.brighton-hove.gov.uk/en-GB/projects/secondary-school-engagement-exercise/1>

I'm going to start by looking at the current catchment areas and how they are proposed to change.


``` r
library(tidyverse)
```

```
## Warning: package 'tidyverse' was built under R version 4.3.3
```

```
## Warning: package 'ggplot2' was built under R version 4.3.3
```

```
## Warning: package 'tidyr' was built under R version 4.3.3
```

```
## Warning: package 'readr' was built under R version 4.3.3
```

```
## Warning: package 'dplyr' was built under R version 4.3.3
```

```
## Warning: package 'stringr' was built under R version 4.3.3
```

```
## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
## ✔ dplyr     1.1.4     ✔ readr     2.1.5
## ✔ forcats   1.0.0     ✔ stringr   1.5.1
## ✔ ggplot2   3.5.1     ✔ tibble    3.2.1
## ✔ lubridate 1.9.3     ✔ tidyr     1.3.1
## ✔ purrr     1.0.2     
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()
## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors
```

``` r
library(sf)
```

```
## Warning: package 'sf' was built under R version 4.3.3
```

```
## Linking to GEOS 3.11.2, GDAL 3.8.2, PROJ 9.3.1; sf_use_s2() is TRUE
```

``` r
library(tmap)
```

```
## Warning: package 'tmap' was built under R version 4.3.3
```

```
## Breaking News: tmap 3.x is retiring. Please test v4, e.g. with
## remotes::install_github('r-tmap/tmap')
```

``` r
"C:/Users/Adam/Documents/BrightonSecondaryCatchments.geojson"
```

```
## [1] "C:/Users/Adam/Documents/BrightonSecondaryCatchments.geojson"
```

