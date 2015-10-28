# Bayesian Regression tutorial
October 27, 2015
Alexis Boukouvalas alexis.boukouvalas@gmail.com


## Files contained:
|File | Description | 
|------------- | -------------|
|BayesianLinearRegression.ppt | Powerpoint slides on Bayesian linear regression |
|BMLR | Folder containing R code for linear regression |
|KruschkeAJ2012.pdf| Paper describing model and approach used in BMLR. Good introduction to Bayesian concepts and assumes no prior knowledge of Bayesian statistics. |
|Gp Regression Example.ipynb| Python notebook demonstrating the use of Gaussian Processes. Uses the python GPy library and does hybrid Monte Carlo sampling. |
|GPLecture6.pdf| Introduction to Gaussian processes. Covers a lot, come and ask me about it. This was not covered in the talk but may be of interest. |

## Setup instructions
R jags:
Install rjags, and jags - for instructions see [here](https://sites.google.com/site/doingbayesiandataanalysis/software-installation). 
Then run BMLRexample.R 

For the Python notebook example of Gaussian Processes you need to install gpy - see [here](https://github.com/SheffieldML/GPy), section Getting started: installing with pip

## Further information
See [this link](http://www.jameskeirstead.ca/blog/gaussian-process-regression-with-r/#code) for R code implementing GP regression.

See [this link](https://theoreticalecology.wordpress.com/2010/09/17/metropolis-hastings-mcmc-in-r/) for a native R implementation of Metropolis Hastings, a basic MCMC variant.

