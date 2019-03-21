# BNOSAC Open R package development repository

This repository contains open R packages developed by BNOSAC not yet published on CRAN.

## Available packages

- To install a package, just type: `install.packages("thepackagename", repos = "https://bnosac.github.io/drat")`
- To see the list of available R packages, do as follows:


```r
pkgs <- available.packages(repos = "https://bnosac.github.io/drat")
pkgs
```


|Package                     |Version |License                     |Depends |Imports                             |Suggests              |
|:---------------------------|:-------|:---------------------------|:-------|:-----------------------------------|:---------------------|
|image.CannyEdges            |0.1.0   |GPL-3                       |NA      |Rcpp (>= 0.12.9)                    |pixmap, knitr         |
|image.ContourDetector       |0.1.0   |AGPL-3 + file LICENSE       |NA      |Rcpp (>= 0.12.8), sp                |knitr, pixmap, magick |
|image.CornerDetectionF9     |0.1.0   |BSD_2_clause + file LICENSE |NA      |Rcpp (>= 0.12.8)                    |pixmap, magick, knitr |
|image.CornerDetectionHarris |0.1.0   |BSD_2_clause + file LICENSE |NA      |Rcpp (>= 0.12.8)                    |magick                |
|image.darknet               |0.1.0   |MIT + file LICENSE          |NA      |NA                                  |NA                    |
|image.DenoiseNLMeans        |0.1.0   |NA                          |NA      |Rcpp (>= 0.12.9), magick, grDevices |NA                    |
|image.dlib                  |0.1.0   |AGPL-3                      |NA      |Rcpp (>= 0.12.9), dlib              |magick                |
|image.libfacedetection      |0.1     |BSD_3_clause + file LICENSE |NA      |Rcpp (>= 0.12.8), graphics          |magick                |
|image.LineSegmentDetector   |0.1.0   |AGPL-3 + file LICENSE       |NA      |Rcpp (>= 0.12.8), sp                |knitr, pixmap, magick |
|image.Otsu                  |0.1     |MIT + file LICENSE          |NA      |Rcpp (>= 0.12.8)                    |magick                |

## File listing

- [`bin/macosx/el-capitan/contrib/3.4/image.ContourDetector_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.4/image.ContourDetector_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.4/image.CornerDetectionF9_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.4/image.CornerDetectionF9_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.4/image.dlib_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.4/image.dlib_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.4/image.LineSegmentDetector_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.4/image.LineSegmentDetector_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.4/image.Otsu_0.1.tgz`](bin/macosx/el-capitan/contrib/3.4/image.Otsu_0.1.tgz)
- [`bin/macosx/el-capitan/contrib/3.4/PACKAGES`](bin/macosx/el-capitan/contrib/3.4/PACKAGES)
- [`bin/macosx/el-capitan/contrib/3.4/PACKAGES.gz`](bin/macosx/el-capitan/contrib/3.4/PACKAGES.gz)
- [`bin/macosx/el-capitan/contrib/3.4/PACKAGES.rds`](bin/macosx/el-capitan/contrib/3.4/PACKAGES.rds)
- [`bin/macosx/el-capitan/contrib/3.5/image.ContourDetector_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.5/image.ContourDetector_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/image.CornerDetectionF9_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.5/image.CornerDetectionF9_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/image.dlib_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.5/image.dlib_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/image.LineSegmentDetector_0.1.0.tgz`](bin/macosx/el-capitan/contrib/3.5/image.LineSegmentDetector_0.1.0.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/image.Otsu_0.1.tgz`](bin/macosx/el-capitan/contrib/3.5/image.Otsu_0.1.tgz)
- [`bin/macosx/el-capitan/contrib/3.5/PACKAGES`](bin/macosx/el-capitan/contrib/3.5/PACKAGES)
- [`bin/macosx/el-capitan/contrib/3.5/PACKAGES.gz`](bin/macosx/el-capitan/contrib/3.5/PACKAGES.gz)
- [`bin/macosx/el-capitan/contrib/3.5/PACKAGES.rds`](bin/macosx/el-capitan/contrib/3.5/PACKAGES.rds)
- [`bin/windows/contrib/3.4/image.CannyEdges_0.1.0.zip`](bin/windows/contrib/3.4/image.CannyEdges_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.ContourDetector_0.1.0.zip`](bin/windows/contrib/3.4/image.ContourDetector_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.CornerDetectionF9_0.1.0.zip`](bin/windows/contrib/3.4/image.CornerDetectionF9_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.CornerDetectionHarris_0.1.0.zip`](bin/windows/contrib/3.4/image.CornerDetectionHarris_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.darknet_0.1.0.zip`](bin/windows/contrib/3.4/image.darknet_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.DenoiseNLMeans_0.1.0.zip`](bin/windows/contrib/3.4/image.DenoiseNLMeans_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.dlib_0.1.0.zip`](bin/windows/contrib/3.4/image.dlib_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.libfacedetection_0.1.zip`](bin/windows/contrib/3.4/image.libfacedetection_0.1.zip)
- [`bin/windows/contrib/3.4/image.LineSegmentDetector_0.1.0.zip`](bin/windows/contrib/3.4/image.LineSegmentDetector_0.1.0.zip)
- [`bin/windows/contrib/3.4/image.Otsu_0.1.zip`](bin/windows/contrib/3.4/image.Otsu_0.1.zip)
- [`bin/windows/contrib/3.4/PACKAGES`](bin/windows/contrib/3.4/PACKAGES)
- [`bin/windows/contrib/3.4/PACKAGES.gz`](bin/windows/contrib/3.4/PACKAGES.gz)
- [`bin/windows/contrib/3.4/PACKAGES.rds`](bin/windows/contrib/3.4/PACKAGES.rds)
- [`bin/windows/contrib/3.5/image.CannyEdges_0.1.0.zip`](bin/windows/contrib/3.5/image.CannyEdges_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.ContourDetector_0.1.0.zip`](bin/windows/contrib/3.5/image.ContourDetector_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.CornerDetectionF9_0.1.0.zip`](bin/windows/contrib/3.5/image.CornerDetectionF9_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.CornerDetectionHarris_0.1.0.zip`](bin/windows/contrib/3.5/image.CornerDetectionHarris_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.darknet_0.1.0.zip`](bin/windows/contrib/3.5/image.darknet_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.DenoiseNLMeans_0.1.0.zip`](bin/windows/contrib/3.5/image.DenoiseNLMeans_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.dlib_0.1.0.zip`](bin/windows/contrib/3.5/image.dlib_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.LineSegmentDetector_0.1.0.zip`](bin/windows/contrib/3.5/image.LineSegmentDetector_0.1.0.zip)
- [`bin/windows/contrib/3.5/image.Otsu_0.1.zip`](bin/windows/contrib/3.5/image.Otsu_0.1.zip)
- [`bin/windows/contrib/3.5/PACKAGES`](bin/windows/contrib/3.5/PACKAGES)
- [`bin/windows/contrib/3.5/PACKAGES.gz`](bin/windows/contrib/3.5/PACKAGES.gz)
- [`bin/windows/contrib/3.5/PACKAGES.rds`](bin/windows/contrib/3.5/PACKAGES.rds)
- [`index.md`](index.md)
- [`index.Rmd`](index.Rmd)
- [`README.md`](README.md)
- [`src/contrib/image.CannyEdges_0.1.0.tar.gz`](src/contrib/image.CannyEdges_0.1.0.tar.gz)
- [`src/contrib/image.ContourDetector_0.1.0.tar.gz`](src/contrib/image.ContourDetector_0.1.0.tar.gz)
- [`src/contrib/image.CornerDetectionF9_0.1.0.tar.gz`](src/contrib/image.CornerDetectionF9_0.1.0.tar.gz)
- [`src/contrib/image.CornerDetectionHarris_0.1.0.tar.gz`](src/contrib/image.CornerDetectionHarris_0.1.0.tar.gz)
- [`src/contrib/image.darknet_0.1.0.tar.gz`](src/contrib/image.darknet_0.1.0.tar.gz)
- [`src/contrib/image.DenoiseNLMeans_0.1.0.tar.gz`](src/contrib/image.DenoiseNLMeans_0.1.0.tar.gz)
- [`src/contrib/image.dlib_0.1.0.tar.gz`](src/contrib/image.dlib_0.1.0.tar.gz)
- [`src/contrib/image.libfacedetection_0.1.tar.gz`](src/contrib/image.libfacedetection_0.1.tar.gz)
- [`src/contrib/image.LineSegmentDetector_0.1.0.tar.gz`](src/contrib/image.LineSegmentDetector_0.1.0.tar.gz)
- [`src/contrib/image.Otsu_0.1.tar.gz`](src/contrib/image.Otsu_0.1.tar.gz)
- [`src/contrib/PACKAGES`](src/contrib/PACKAGES)
- [`src/contrib/PACKAGES.gz`](src/contrib/PACKAGES.gz)
- [`src/contrib/PACKAGES.rds`](src/contrib/PACKAGES.rds)
