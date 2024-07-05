# bayes-net-pymc-example

This repo attempts to model a simple bayesian network using pymc.

The modelling and sampling appears to work well for the most part but I am struggling to get correct results when using the model for out-of-sample predictions.

Open questions:  
- Is this modelling approach correct?
- Is the approach for generating out of sample predictions correct?
- Why can't I generate posteriors for the observed nodes?

# Requirements
`python 3.12` and `graphviz`. Python packages are listed in `requirements.txt`.