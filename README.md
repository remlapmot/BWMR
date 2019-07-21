# BWMR
BWMR (Bayesian Weighted Mendelian Randomization), is an efficient statistical method to infer the causality between a risk exposure factor and a trait or disease outcome, based on GWAS summary statistics. 'BWMR' package provides the estimate of causal effect with its standard error and the P-value under the test of causality.


# Installation
To install the development version of BWMR, it's easiest to use the 'devtools' package.
```
# install.packages("devtools")
library(devtools)
install_github("jiazhao97/BWMR")
```


# Usage
[The 'BWMR' vignette](https://github.com/jiazhao97/BWMR/blob/master/vignettes/BWMR_package.pdf?raw=true) will provide a good start point for Mendelian randomization analysis using BWMR package. The following help page will also provide quick references for BWMR package and the example command lines:
```
library(ggplot2)
library(BWMR)
example(BWMR)
```


# Development
This R package is developed by Jia Zhao.

