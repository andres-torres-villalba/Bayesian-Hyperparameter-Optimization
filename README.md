# Bayesian Hyperparameter Optimization

"""The Hyperparameter Optimization uses the acquisition funtion
(maximize this to improve the GP)

EI(x) = E [max {0,f8x9 - f(^x)}] ,

This will explore the high dimensionality space of the hyperparameters and works
to maximize the acquaracy of the models while they are being trained by changing 
the hyper parameters."""

