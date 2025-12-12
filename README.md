# Black–Scholes Pricing Engine  Greeks & Implied Volatility

This repository implements a Black–Scholes pricing engine in Python with:

closed-form pricing for European calls and puts;

analytical Greeks (Delta, Gamma, Vega, Theta, Rho);

an implied volatility solver (Newton–Raphson with bisection fallback);

volatility smile plotting across strikes;


## Motivation

This mini-project is intended as a natural continuation after a binomial introduction. It provides the fundamental tools to:

price European options,

understand and compute sensitivities used in hedging,

extract market implied volatility and visualize the smile.

## Theory / References

The implementation follows classical references:

John C. Hull — Options, Futures and Other Derivatives (Black–Scholes theory, Greeks)

Paul Wilmott — Introduces Quantitative Finance (intuition and practical points)

Yves Hilpisch — Python for Finance (implementation guidance)

## How to use

Open the provided single-cell script in Google Colab.

Run the cell  it will compute example prices, Greeks, implied vols and display smile plots.

Change parameters (S, K, r, sigma, T) to explore other cases.

## Next steps / Extensions

Calibrate volatility surface to market option quotes

Monte Carlo pricing for exotic options

Local volatility / stochastic volatility models (Heston, SABR)

Route to trading strategies (volatility spreads, calendar spreads, delta-hedged P/L analysis)

## Dependencies

Python 3.x

numpy

scipy

matplotlib

pandas (for optional tabular output)

License & Author

Author: Andrés Rendón 
