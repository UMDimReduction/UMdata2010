# UMdata2010


This package contains interactive tutorials used for teaching DATA2010--Tools and Techniques for Data Science at the University of Manitoba.

To install this package, make sure you have the `remotes` package available:
```{r echo=TRUE}
install.packages("remotes")
remotes::install_github("UMDimReduction/UMdata2010")
```
To run a tutorial, run the following code:
```{r echo=TRUE}
learnr::run_tutorial("test", package = "UMdata2010")
```
The first argument is the name of the tutorial.

## List of tutorials
These are the planned tutorials:

1. `Knn`: K-nearest Neighbors Algorithm

2. `ClassificationTree`: Classification Tree

3. `RegressionTree`: Regression Tree



