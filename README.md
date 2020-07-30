# Stein Variational Gradient Descend
A simple application of Stein Variational Gradient Descend including some visualizations. This has been put together as part of the lecture [Monte Carlo Methods in Machine Learning and Artificial Intelligence](https://moseskonto.tu-berlin.de/moses/modultransfersystem/bolognamodule/beschreibung/anzeigen.html?number=40584&version=5&sprache=2) at TU Berlin.

# What is it?

Stein variational Gradient Descend (SVGD) is a Monte Carlo Method used to draw samples from a target distribution. Starting with a set of particles drawn from a reference distribution, it uses Gradient Descend in a RKHS to find transformations for the particles. By iteratively applying these transformations, the particles will then converge towards the target distribution. \
<img src="/presentation/svgd_mvn.gif" width="860">

# References
_Paper_: Liu, Qiang and Wang, Dilin (2016). Stein Variational Gradient Descent: A General Purpose Bayesian Inference Algorithm ([arXiv.org](https://arxiv.org/abs/1608.04471))

_Code_: [github.com/DartML/Stein-Variational-Gradient-Descent](https://github.com/DartML/Stein-Variational-Gradient-Descent) \
This is where the SVGD kernel and update functions are from.
