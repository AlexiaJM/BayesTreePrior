# BayesTreePrior

[![](http://cranlogs.r-pkg.org/badges/BayesTreePrior)](http://cran.rstudio.com/web/packages/BayesTreePrior/index.html)
[![](http://cranlogs.r-pkg.org/badges/grand-total/BayesTreePrior)](http://cran.rstudio.com/web/packages/BayesTreePrior/index.html)

BayesTreePrior is a R package for the simulation of the prior distribution of bayesian trees by Chipman et al. (1998). 
The prior distribution of the trees is highly dependent on the design matrix X, therefore using the suggested hyperparameters 
by Chipman et al. (1998) is not recommended and could lead to unexpected prior distribution.
This work is part of my master thesis (http://www.archipel.uqam.ca/8973/).

To install the latest GitHub development version, run in R :

install.packages("devtools")

devtools::install_github("AlexiaJM/BayesTreePrior")
