---
title: BNOSAC Open R package development repository
layout: post
---

# bnosac/bnosac.drat

This repository contains open R packages developed by BNOSAC not yet published on CRAN.

## Available packages


```r
available.packages(repos = "https://bnosac.github.io/drat")
```

```
##                         Package                   Version Priority Depends
## image.CornerDetectionF9 "image.CornerDetectionF9" "0.1.0" NA       NA     
## image.Otsu              "image.Otsu"              "0.1"   NA       NA     
##                         Imports            LinkingTo
## image.CornerDetectionF9 "Rcpp (>= 0.12.8)" "Rcpp"   
## image.Otsu              "Rcpp (>= 0.12.8)" "Rcpp"   
##                         Suggests                Enhances
## image.CornerDetectionF9 "pixmap, magick, knitr" NA      
## image.Otsu              "magick"                NA      
##                         License                       License_is_FOSS
## image.CornerDetectionF9 "BSD_2_clause + file LICENSE" NA             
## image.Otsu              "MIT + file LICENSE"          NA             
##                         License_restricts_use OS_type Archs
## image.CornerDetectionF9 NA                    NA      NA   
## image.Otsu              NA                    NA      NA   
##                         MD5sum                            
## image.CornerDetectionF9 "5cdb01b2c35fc12f6963c504cb73d9e3"
## image.Otsu              "f6a259b0f32a6309d269c836ae23790c"
##                         NeedsCompilation File
## image.CornerDetectionF9 "yes"            NA  
## image.Otsu              "yes"            NA  
##                         Repository                                 
## image.CornerDetectionF9 "https://bnosac.github.io/drat/src/contrib"
## image.Otsu              "https://bnosac.github.io/drat/src/contrib"
```

## To install a package

```
install.packages("...", repos = "https://bnosac.github.io/drat")
``` 

## File listing

- [`bin/macosx/el-capitan/contrib/3.5/image.CornerDetectionF9_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.5/image.CornerDetectionF9_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/image.Otsu_0.1.tgz`](bin/macosx/el-capitan/contrib/3.5/image.Otsu_0.1.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/PACKAGES`](bin/macosx/el-capitan/contrib/3.5/PACKAGES)
- [`bin/macosx/el-capitan/contrib/3.5/PACKAGES.gz`](bin/macosx/el-capitan/contrib/3.5/PACKAGES.gz)
- [`bin/macosx/el-capitan/contrib/3.5/PACKAGES.rds`](bin/macosx/el-capitan/contrib/3.5/PACKAGES.rds)
- [`index.md`](index.md)
- [`index.Rmd`](index.Rmd)
- [`README.md`](README.md)
- [`src/contrib/image.CornerDetectionF9_0.1.0.tar.gz`](src/contrib/image.CornerDetectionF9_0.1.0.tar.gz)
- [`src/contrib/image.Otsu_0.1.tar.gz`](src/contrib/image.Otsu_0.1.tar.gz)
- [`src/contrib/PACKAGES`](src/contrib/PACKAGES)
- [`src/contrib/PACKAGES.gz`](src/contrib/PACKAGES.gz)
- [`src/contrib/PACKAGES.rds`](src/contrib/PACKAGES.rds)
