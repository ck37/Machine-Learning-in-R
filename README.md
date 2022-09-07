# Machine Learning in R

This is the repository for Chris’s Machine Learning in R workshop. [View the associated slides here](https://ck37.github.io/Machine-Learning-in-R/slides.html#1).

RStudio Binder:
[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/ck37/Machine-Learning-in-R/main?urlpath=rstudio)

[RStudio Cloud project](https://rstudio.cloud/content/4460169)

## Content outline

  - Background on machine learning
      - Classification vs regression
      - Performance metrics
  - Data preprocessing
      - Missing data
      - Train/test splits
  - Algorithm walkthroughs
      - Lasso
      - Decision trees
      - Random forests
      - Gradient boosted machines
      - SuperLearner ensembling
  - Challenge questions  
  
## Getting started

Please follow the notes in [participant-instructions.md](participant-instructions.md).  

#### HAVE FUN! :^)

The seven algorithm R Markdown files (lasso, decision tree, random forest, xgboost, SuperLearner, PCA, and clustering) are designed to function in a standalone manner.  

After installing and librarying the packages in 01-overview.Rmd, run all the code in 02-preprocessing.Rmd to preprocess the data. Then, open any one of the seven algorithm R Markdown files and "Run All" code to see the results and visualizations! 

## Assumed participant background

We assume that participants have familiarity with:

* Basic R syntax
* Statistical concepts such as mean and standard deviation

## Technology requirements

Please bring a laptop with the following:

* [R version](https://cloud.r-project.org/)
3.5 or greater
* [RStudio integrated development environment (IDE)](https://www.rstudio.com/products/rstudio/download/#download) is
highly recommended but not required.

## Resources

Browse resources listed on the [D-Lab Machine Learning Working Group repository](https://github.com/dlab-berkeley/MachineLearningWG). Scroll down to see code examples in R and Python, books, courses at UC Berkeley, online classes, and other resources and groups to help you along your machine learning journey!  

## Slideshow

The slides were made using [xaringan](https://github.com/yihui/xaringan), which is a wrapper for [remark.js](https://remarkjs.com/#1). Check out Chapter 7 if you are interested in making your own! The theme borrows from Brad Boehmke's presentation on [Decision Trees, Bagging, and Random Forests - with an example implementation in R](https://bradleyboehmke.github.io/random-forest-training/slides-source.html#1).  

