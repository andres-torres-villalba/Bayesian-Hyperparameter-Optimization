# Bayesian Hyperparameter Optimization

"""The Hyperparameter Optimization uses the acquisition funtion
(maximize this to improve the GP)

EI(x) = E [max {0,f8x9 - f(^x)}] ,

This will explore the high dimensionality space of the hyperparameters and finds the
hyperparamters that better improve the acquracy of the models. This is done while 
the models are being trained."""


