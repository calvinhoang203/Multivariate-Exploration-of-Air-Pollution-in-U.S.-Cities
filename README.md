# Multivariate-Exploration-of-Air-Pollution-in-U.S.-Cities



## Prerequisites

* R (version 4.0 or higher)
* RStudio (optional but recommended)
* Internet connection to install packages

## Installation

Open R (or RStudio) and run:

```r
install.packages(c(
  "mlbench",   # Glass & Pima datasets
  "HSAUR2",    # US air pollution dataset
  "ggplot2",   # Visualization
  "dplyr"      # Data manipulation
))
```

## Loading Libraries

At the top of your script or R Markdown file, include:

```r
library(mlbench)
library(HSAUR2)
library(ggplot2)
library(dplyr)
```

## Loading a Dataset

```r
# US Air Pollution dataset
# data(USairpollution)
```



## Next Steps

Proceed with your chosen multivariate technique:

* **PCA** or factor analysis: calculate eigenvalues, choose principal components, interpret loadings.
* **LDA/QDA**: split into training and test sets, fit the model, plot decision boundaries, compute confusion matrix.

Include your R code outputs, plots, interpretations, and conclusions in your final report. At the end of your report, specify each group member’s contributions.

