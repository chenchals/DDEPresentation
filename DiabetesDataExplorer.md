<style>
.small-font pre code {font-size: 0.5em;},
.column { float: left; margin: 0 2.5% 1em 0; width: 22.5%; },
.column:nth-child(4n) { margin-right: 0; },
.column:nth-child(4n+1) { clear: left; }
</style>
DiabetesDataExplorer
========================================================
author: Chenchals
date: December 12/27/15 2015
transition: rotate
<hr>
<small>
Coursera Course: Data Science Specialization<br>
09-Developing Data Products
</small>

Diabetes Research
========================================================

Diabetes is a disease where patients have chronically high levels of _glucose_ in the blood.  This is primarily caused by the inability of __pancreas__ to produce _insulin_, a hormone that regulates the level of sugar in the blood.<p>

The [Diabetes Data Explorer (DDE)](https://chenchalscoursera.shinyapps.io/DiabetesDataExplorer) helps to explore and model the various _predictors_. DDE can do model based prediction of the probability of disease for any arbitarary set of predictor values.<p>

DDE currently uses data from the [UCI Machine Learning](https://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.names) repository on the prevelance of diabetes in Pima Indians.

Diabetes Data Explorer - Navbar
========================================================
![plot of chunk unnamed-chunk-1](DiabetesDataExplorer-figure/unnamed-chunk-1-1.png) 
***
<span style="font-size:9;">__Predictors:__ Factors that affect the disease outcome. Choose two or more of these predictors to explore.</span><br>
<span style="font-size:9;">__Select All Predictors:__ A one shot selection or de-selection of all _Predictors_</span><br>
<span style="font-size:9;">__Use Data:clean__ Removes rows, where the values of rthe _predictors_ are not sensible.  Example a _BMI_ of 0</span><br>
<span style="font-size:9;">__Use Data:raw__ Use all rows, even if the value for a _predictor_ is not sensible</span>

Diabetes Data Explorer - Explore & Analyze
========================================================
<span style="float:left; width:50%; text-align:center;">
![data](images/data.png) <br><br><br>
**Data Tab:<br> Explore selected predictor summary statistics**
</span>
<span style="float:right; width:50%; text-align:center;">
![data](images/prepare.png)
**Prepare Tab:<br>** **Explore selected predictor interactions in scatterplots**
</span>

Diabetes Data Explorer - Prediction & Future
========================================================

<span style="float:left; width:40%; text-align:center;">
![data](images/prediction.png)
</span>
**Prediction Tab:<br> Explore model prediction for arbitarary predictor values**
<br>
<br>
<br>
<br>
<hr>
**Future**<br>
&nbsp;&nbsp;&nbsp;Prepare: Add correlations to the scatterplot using _ggpairs_<br>
&nbsp;&nbsp;&nbsp;Prediction: Add different _models_, _learning algoriths_, _accuracy_, etc.,<br>
**Bibliography**<br>
&nbsp;&nbsp;&nbsp;The DDE is mostly based on the [diabetes homework](http://www.stat.cmu.edu/~cshalizi/402/hw/07/solutions-07.pdf) of CMU.



