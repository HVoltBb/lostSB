# lastSB
An R package of bycatch **l**oss **a**nalysi**s** **t**ools for **S**ea**B**irds in longline fisheries

This is a companian package of a manuscript pending review with the title "Design and analysis of seabird bycatch loss in longline fisheries" by Can Zhou et al. The specifics of the statistical model are described in that manuscript, details of which will be provided here as soon as possible.

## Introduction to seabird bycatch in longline fisheries
[to be added]

## How to install
First, you will need R package _devtools_. Run the following command in R, if you don't have devtools on your computer.
```R
install.packages('devtools') # You don't need this line if you already have it on you computer
```
Either one of the following method can be used to install and load lastSB package:

* Download the zip file of lastSB package from GitHub, unzip it to your working directory on your computer, and run the following commands in R,
```R
devtools::install('lastSB')
library(lastSB)
```
* For this method, you don't need to download anything manually, but a live internet connection at the time of installation. Just run the following two lines of code and you are all set,
```R
devtools::install_github("HVoltBb/lastSB")
library(lastSB)
```

The functionality of this package depends on JAGS 4.X.X, which can be downloaded at <http://mcmc-jags.sourceforge.net>.

## Build-in dataset
Data of the seabird interaction observations at setting and carcass confirmation at the haul by Nigel Brothers (2010) are included in this package. The type of the last observed bait-taking attempt, the distance astern at which the attempt occured, and the final confirmation of carcass retrieval at the haul for _c._ 3000 interactions are included.

This dataset was extracted using Adobe Acrobat XI from a PDF of the report prepared by Nigel Brothers (2008). The original dataset is owned by NB.

* Zhou, C., et al. 20XX. Design and analysis of seabird bycatch loss in longline fisheries. Under review.
* Brothers, N., et al. 2010. Seabird bycatch in pelagic longline fisheries is grossly underestimated when using only haul data. PLoS ONE 5(8): e12491
* Brothers, N. 2008. How accurate are observer reported kills of albatrosses on longlines? Final report. Duke University & Blue Ocean Institute.

