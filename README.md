# Insurance & Finance Projects

This repository collects a set of quantitative finance and actuarial science projects developed in Python through Jupyter notebooks.

The main objective is to explore numerical methods, statistical models and machine learning techniques applied to problems in insurance pricing, risk modelling, stochastic processes and financial modelling.

## Repository Overview

The repository currently includes projects related to:

- actuarial pricing and claim frequency modelling;
- compound loss distribution approximation;
- stochastic volatility models;
- option pricing under the Heston model;
- Hidden Markov Models with autoregressive dynamics;
- online Expectation-Maximization algorithms;
- machine learning applications in insurance.

## Projects

| Notebook | Description |
|---|---|
| `Compound_Dist_Approx.ipynb` | Approximation of compound loss distributions using actuarial techniques, including translated distributions, Edgeworth approximation, Kolmogorov-Smirnov testing and Panjer recursion. |
| `Heston.ipynb` | Simulation and pricing toolkit for a Heston-type stochastic volatility model. The notebook includes CIR variance dynamics, Quadratic Exponential simulation scheme and option pricing routines. |
| `OnlineHMMAR1.ipynb` | Implementation of an online Expectation-Maximization algorithm for an autoregressive Hidden Markov Model of order 1, HMM-AR(1), with simulation and forecasting components. |
| `PoissonPricing.ipynb` | Application of statistical and machine learning models to non-life insurance pricing, with a focus on claim frequency modelling using the `freMTPL2freq` motor insurance dataset. |
| `PoissonPricing2.ipynb` | Additional experiments and extensions related to Poisson-based insurance pricing models. |

## Main Topics

### Insurance

The insurance-related notebooks focus on actuarial modelling and pricing techniques, including:

- claim frequency modelling;
- Poisson regression and Generalized Linear Models;
- machine learning approaches for non-life insurance pricing;
- compound loss distribution approximation;
- Panjer recursion;
- comparison of approximation methods for aggregate claims.

### Finance

The finance-related notebooks focus on stochastic processes and quantitative modelling, including:

- stochastic volatility modelling;
- Heston model simulation;
- CIR variance process;
- option pricing;
- regime-switching time series models;
- Hidden Markov Models;
- online parameter estimation.

## Technologies Used

The projects are mainly developed in Python and Jupyter Notebook.

Main libraries used across the repository include:

- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `statsmodels`
- `scikit-learn`
- `tensorflow / keras`

Additional libraries may be used in specific notebooks depending on the model implemented.

## Repository Structure

```text
Insurance-Finance-project/
│
├── Compound_Dist_Approx.ipynb
├── Heston.ipynb
├── OnlineHMMAR1.ipynb
├── PoissonPricing.ipynb
├── PoissonPricing2.ipynb
└── README.md
