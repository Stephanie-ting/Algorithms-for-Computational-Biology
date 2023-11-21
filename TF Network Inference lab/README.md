This lab is about "TF Network Inference from gene expression data after TF perturbation". It will process actual yeast gene expression taken at time points after the induction (i.e. activation) of a transcription factor (TF).

The overall approach is LASSO, a.k.a L1 regularized or penalized regression. In each regression run, a parameter called lambda is selected by cross-validation. The optimization chooses coefficients that minimize the the sum of the squared errors plus lambda times the sum of the absolute values of the coefficients. 
