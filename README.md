# wine-quality
An R exercise on linear regression and k-Nearest Neighbors predictive modelling techniques. The task is to predict the quality of red wines given their attributes. Quality scores range between 0-10; 0=very bad, 10=excellent. The dataset was taken from <a href= https://archive.ics.uci.edu/ml/datasets/Wine+Quality> here </a>.

Two models were built:
* Linear regression with stepwise (forward) subset selection.
* k-Nearest Neighbors (kNN) with principal components as input.

The cross validation method was used for choosing the model parameters and input variables.

Packages: caret, MASS, RWeka, kknn