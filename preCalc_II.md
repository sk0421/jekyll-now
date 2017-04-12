---
layout: page
title: PreCalculus Section II
link: PreCalulus
background:
  -url: logo.png
---

**Section II: Modeling Data with Functions**

In this section, we aim to familiarize students with basic modeling of data using Least Squares techniques.  First, we demonstrate some simple 
examples to introduce the technique of minimizing the RMSE in linear regression.  Next, we show how to transform exponential data
to linear data with logarithms as a way to perform regression on non-linear functions.  We also demonstrate how to use polynomial regression 
in numpy.  Finally, students are introduced to an alternative take on regression with scikitlearn and a Machine Learning approach
to regression.

**Materials**

The materials here are structured in three notebooks, however you may want to explore these for extended periods of time.  They are not meant to 
imply a single class would accomplish the ideas.

- [Notebook 2.1](): **An introduction to regression and least squares**.  Students perform least squares on small data sets represented as lists in 
Python as an introduction to the technique of Ordinary Least Squares.  Next, students understand how to use both numpy's polyfit and scipy's linear regression
functionality to fit lines to data.

- [Notebook 2.2](): **Non - Linear Regression.**  Here, we demonstrate the effect of tranforming a non-linear dataset with logarithms as a way
to linearize data.  Next, the correlation coefficient is discussed and determined with numpy and scipy.  Finally, we use these techniques to examine
a dataset that may be exponential or polynomial.

- [Notebook 2.3](): **Machine Learning and Bayesian Thinking**: In this notebook we introduce students to approaching regression problems
from a machine learning perspective.  Some examples using scikitlearn and the builtin Boston Housing and Diabetes datasets drive these explorations.
