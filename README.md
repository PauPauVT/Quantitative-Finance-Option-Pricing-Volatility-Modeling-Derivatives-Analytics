# Quantitative Finance Option Pricing, Volatility Modeling & Derivatives Analytics
Option Pricing Engines for European, American and Exotic Options

## Overview

This repository presents a comprehensive implementation of modern quantitative finance models for pricing financial derivatives, analyzing volatility dynamics, and exploring numerical methods used in contemporary option pricing.

The project combines rigorous mathematical foundations with practical Python implementations, covering analytical pricing formulas, lattice methods, Monte Carlo simulations, stochastic volatility models, calibration techniques, and a wide range of exotic derivatives.

Rather than focusing on a single pricing framework, this repository provides a unified environment for studying, comparing, and visualizing multiple methodologies under consistent assumptions.

The project has been developed for educational purposes, quantitative research and portfolio demonstration, showcasing both the mathematical foundations and computational implementation of derivative pricing.

---

# Key Features

- Analytical pricing models
- Numerical pricing algorithms
- American option pricing
- Exotic derivatives pricing
- Stochastic volatility models
- Jump diffusion processes
- Model calibration
- Implied volatility estimation
- Greeks computation
- Interactive Streamlit dashboard
- Financial visualizations
- Market data integration

---

## Pricing Models

### European Options

- Black-Scholes-Merton
- Black-Scholes with Continuous Dividend Yield
- Cox-Ross-Rubinstein Binomial Tree
- Monte Carlo Simulation
- Implied Volatility Solver
- Greeks Analysis

---

### American Options

- Cox-Ross-Rubinstein Tree
- Bjerksund-Stensland (2002) Approximation
- Least Squares Monte Carlo (Longstaff-Schwartz under Heston dynamics)
- Early Exercise Premium Analysis
- Greeks for American Options

---

### Exotic Options

#### Asian Options

- Arithmetic Average Price
- Geometric Average Price

#### Barrier Options

- Up-and-In
- Up-and-Out
- Down-and-In
- Down-and-Out

#### Binary Options

- Cash-or-Nothing
- Asset-or-Nothing

#### Gap Options

#### Forward Start Options

#### Compound Options

#### Chooser Options

#### Lookback Options

- Floating Strike
- Fixed Strike

---

## Volatility Models

### Constant Volatility

- Black-Scholes Volatility

### Stochastic Volatility

- Heston Model
- Heston Monte Carlo Simulation

### Jump Models

- Merton Jump Diffusion

---

## Calibration

The repository includes model calibration routines allowing theoretical models to be fitted to observed market prices.

Implemented calibration techniques include:

- Heston Model Calibration
- SABR Calibration
- Volatility Surface Construction
- Implied Volatility Extraction
- Numerical Optimization

---

## Numerical Methods

- Closed-form analytical solutions
- Binomial trees
- Monte Carlo simulation
- Numerical optimization
- Root-finding algorithms
- Regression-based Monte Carlo
- Numerical integration

---

## Greeks

First and second order sensitivities include:

- Delta
- Gamma
- Vega
- Theta
- Rho

---

## Interactive Dashboard

The project includes a Streamlit application providing an interactive environment for:

- Pricing derivatives
- Exploring volatility smiles
- Visualizing stochastic processes
- Comparing pricing models
- Displaying Greeks
- Inspecting Monte Carlo simulations
- Market data exploration

---

## Mathematical Background

The repository implements methodologies introduced in the seminal works of

- Black & Scholes (1973)
- Merton (1973, 1976)
- Cox, Ross & Rubinstein (1979)
- Longstaff & Schwartz (2001)
- Bjerksund & Stensland (2002)
- Heston (1993)

along with modern volatility modeling techniques.

---

## Technologies

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib
- Plotly
- Streamlit
- yfinance
- FRED API
- SciPy Optimize

---

## Repository Contents

```
.
├── European Option Pricing
├── American Option Pricing
├── Exotic Option Pricing
├── Volatility Models
├── Calibration
├── Greeks
├── Streamlit Dashboard
├── Market Data
├── Visualizations
└── Documentation
```

---

## Learning Outcomes

This project demonstrates practical applications of

- Stochastic Calculus
- Risk-Neutral Valuation
- Numerical Methods
- Financial Engineering
- Computational Finance
- Derivative Pricing
- Volatility Modeling
- Model Calibration
- Scientific Computing

---

## Applications

Suitable for

- Quantitative Finance
- Financial Engineering
- Academic Research
- Derivatives Pricing
- Risk Management
- Portfolio Projects
- Teaching Computational Finance

---

## Limitations

Although the repository implements a broad collection of pricing models, it is primarily intended as an educational and research project rather than a production trading platform.

Current limitations include:

- European and selected American/exotic contracts only
- No transaction cost or liquidity modelling
- Deterministic interest rates in most pricing frameworks
- Limited multi-asset support
- Calibration quality depends on market data availability
- Monte Carlo methods remain computationally expensive
- No GPU acceleration
- No parallel pricing engine

---

## References

Black, F. & Scholes, M. (1973)

Merton, R. C. (1973, 1976)

Cox, Ross & Rubinstein (1979)

Heston, S. (1993)

Longstaff & Schwartz (2001)

Bjerksund & Stensland (2002)

Hull, J. C.

Gatheral, J.

Wilmott, P.

---

## Author

**Pau Vendrell**

Quantitative Finance • Derivatives Pricing • Stochastic Volatility • Computational Finance • Python
