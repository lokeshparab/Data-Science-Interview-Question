# Data Analytics Questions

## 1. RoC Curves

An ROC curve (**receiver operating characteristic curve**) is a graph showing the performance of a classification model at all classification thresholds.
This curve plots two parameters

* **True Positive Rate** is a synonym for **recall or sensitivity** and is therefore defined as follows: 

 $$TRP =\frac{TP}{TP + FN}$$
* **False Positive Rate** defined as follows:

 $$FRP =\frac{FP}{FP + TN}$$
 
 An ROC curve plots TPR vs. FPR at different classification thresholds. Lowering the classification threshold classifies more items as positive, 
 thus increasing both False Positives and True Positives. The following figure shows a typical ROC curve
 
 ![](https://developers.google.com/static/machine-learning/crash-course/images/ROCCurve.svg)
