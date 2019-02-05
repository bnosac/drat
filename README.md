# BNOSAC Open R package development repository

This repository contains open R packages developed by BNOSAC not yet published on CRAN.

## Available packages

- To install a package, just type: `install.packages("thepackagename", repos = "https://bnosac.github.io/drat")`
- To see the list of available R packages, do as follows:


```r
pkgs <- available.packages(repos = "https://bnosac.github.io/drat")
pkgs
```


|Package                 |Version |License                     |Depends |Imports          |Suggests              |
|:-----------------------|:-------|:---------------------------|:-------|:----------------|:---------------------|
|image.CornerDetectionF9 |0.1.0   |BSD_2_clause + file LICENSE |NA      |Rcpp (>= 0.12.8) |pixmap, magick, knitr |
|image.Otsu              |0.1     |MIT + file LICENSE          |NA      |Rcpp (>= 0.12.8) |magick                |

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
