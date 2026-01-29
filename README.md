# European-Market-Stock-Simulation-Risk-Analysis
European market stock &amp; portfolio risk simulation using Monte Carlo methods, Geometric Brownian Motion, and data-driven risk metrics (VaR, loss probability) for quantitative finance modeling.
# European Market Stock Simulation & Risk Analysis


## Markets & Assets Used

### Index-level simulation

* **EURO STOXX 50** (`^STOXX50E`)
  Broad European market benchmark

### Portfolio-level simulation

European large-cap diversified portfolio:

* **ASML** (Netherlands) → `ASML.AS`
* **SAP** (Germany) → `SAP.DE`
* **LVMH** (France) → `MC.PA`

This structure ensures:

* Cross-country exposure
* Sector diversification
* Lower correlation bias
* Realistic portfolio risk dynamics

---

## Core Model

### Geometric Brownian Motion (GBM)

Stock prices are modeled using the stochastic process:

Sₜ₊₁ = Sₜ · exp((μ − ½σ²)Δt + σ√Δt · Zₜ)

Where:

* **μ** = expected return (drift)
* **σ** = volatility
* **Δt** = time step
* **Zₜ** = standard normal random shock

This model captures:

* Continuous growth
* Random market fluctuations
* Log-normal price distributions

---

## Simulation Framework

### Techniques used:

* Monte Carlo simulation (10,000+ paths)
* Stochastic price modeling (GBM)
* Portfolio aggregation
* Probabilistic forecasting
* Distribution-based risk analysis

---

## Risk Metrics

The system computes:

* **Value at Risk (VaR)**
  Worst expected loss at a given confidence level

* **Probability of Loss**
  Probability of portfolio value falling below initial capital

* **Distribution of outcomes**
  Full probabilistic future value spectrum

---

## Portfolio Modeling

The multi-asset model simulates:

* Individual asset GBM paths
* Portfolio aggregation via weights
* Correlated market dynamics
* Scenario-based portfolio evolution

This enables realistic modeling of:

* Diversification effects
* Risk concentration
* Tail-risk exposure
* Downside scenarios

---

## Quantitative Skills Demonstrated

* Stochastic processes
* Monte Carlo simulation
* Financial modeling
* Portfolio risk analysis
* Probabilistic forecasting
* Data-driven parameter estimation
* Quantitative risk metrics
* European market modeling

---

## Applications

This framework reflects real methodologies used in:

* Quantitative research
* Risk management
* Asset management
* Trading strategy research
* Financial engineering
* Portfolio optimization

---

## Credits

Original project format inspired by:

**Kyle Dickinson (Quant_Kyle)**
GitHub: [https://github.com/k-dickinson](https://github.com/k-dickinson)

This project is an adapted and extended implementation using European markets, alternative assets, and market-specific modeling assumptions.

---

## Resources ssed

* GBM Article: QuantStart
  [https://www.quantstart.com/articles/geometric-brownian-motion-simulation-with-python/](https://www.quantstart.com/articles/geometric-brownian-motion-simulation-with-python/)

* GBM Video: Dummy R
  [https://www.youtube.com/watch?v=5A2iNvpAv1w](https://www.youtube.com/watch?v=5A2iNvpAv1w)

* Monte Carlo Video: MarbleScience
  [https://www.youtube.com/watch?v=7ESK5SaP-bc](https://www.youtube.com/watch?v=7ESK5SaP-bc)

* Monte Carlo Video: IBM Technology
  [https://www.youtube.com/watch?v=7TqhmX92P6U](https://www.youtube.com/watch?v=7TqhmX92P6U)
