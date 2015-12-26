DiabetesDataExplorer
========================================================
author: Chenchals
date: December 12/26/15 2015
transition: rotate
<hr>
<small>
Coursera Course: Data Science Specialization<br>
09-Developing Data Products
</small>

Diabetes Research
========================================================

Diabetes is a disease where patients have chronically high levels of _glucose_ in the blood.  This is primarily caused by the inability of __pancreas__ to produce _insulin_, a hormone that regulates the level of sugar in the blood.<p>

The __Diabetes Data Explorer__ helps to explore the dependency of various _predictors_ that fortell if a person is having diabetes.  It uses data from the [UCI Machine Learning](https://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.names) repository on the prevelance of diabetes in Pima Indians.


Diabetes Data Explorer - Navbar
========================================================

![plot of chunk unnamed-chunk-1](DiabetesDataExplorer-figure/unnamed-chunk-1-1.png) 
***
- __Predictors:__ Factors that affect the disease outcome. Choose two or more of these predictors ot explore the data.
- __Select All Predictors:__ A one shot selection or de-selection of all _Predictors_
- __Use Data:__ 
  - __clean__ Removes rows, where the values of rthe _predictors_ are not sensible.  Example a _BMI_ of 0
  - __raw__ Use all rows, even if the value for a _predictor_ is not sensible

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 
