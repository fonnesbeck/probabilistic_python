# Probabilistic Python: An Introduction to Bayesian Modeling with PyMC
PyData London 2022 Tutorial

Bayesian statistical methods offer a powerful set of tools to tackle a wide variety of data science problems. In addition, the Bayesian approach generates results that are easy to interpret and automatically account for uncertainty in quantities that we wish to estimate and predict. Historically, computational challenges have been a barrier, particularly to new users, but there now exists a mature set of probabilistic programming tools that are both capable and easy to learn. We will use the newest release of PyMC (version 4) in this tutorial, but the concepts and approaches that will be taught are portable to any probabilistic programming framework.

This tutorial is intended for practicing and aspiring data scientists and analysts looking to learn how to apply Bayesian statistics and probabilistic programming to their work. It will provide learners with a high-level understanding of Bayesian statistical methods and their potential for use in a variety of applications. They will also gain hands-on experience with applying these methods using PyMC, specifically including the specification, fitting and checking of models applied to a couple of real-world datasets.

As this is an introductory tutorial, no direct experience with PyMC or Bayesian statistics will be required. However, to benefit maximally from the tutorial, learners should have some familiarity with basic statistics (things like regression and estimation) and with core components of the scientific Python stack (e.g. NumPy, pandas and Jupyter).

## Outline
1. The basics of Bayes (10 min)
    - Bayesian intuition
    - What is a probabilistic model?
    - Solving a simple model without specialized software
2. Building models in PyMC (20 min)
   - Picking prior distributions
   - The data-generating model
   - Transformed variables
3. Estimating models with Markov chain Monte Carlo (25 min)
    - How can we estimate a model with sampling?
    - The Hamiltonian Monte Carlo algorithm
    - MCMC in PyMC
    - What to do when things go wrong
4. Model checking (15 min)
    - Summarizing your model with plots and tables
    - Did our inference algorithm work as expected
    - Is our model generating reasonable and believable results?
5. The Bayesian workflow (20 min)
    - A complete working example, from data import through to interpreting the results