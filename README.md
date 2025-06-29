# OPTIONS_FILE
# 📈 Options Pricing and Strategy Simulator

This repository provides interactive notebooks for understanding **Call and Put options**, implementing the **Binomial Tree** and **Black-Scholes** pricing models, and working through practical examples and problems in options trading.

---

## 📂 Contents

### 🧮 1. `call_put_application.ipynb` — Call and Put Options Simulator

- Simulates European **call** and **put** options.
- Visualizes **payoff diagrams** and **profit/loss** outcomes.
- Allows customization of:
  - Strike Price
  - Spot Price
  - Time to Expiry
  - Volatility
  - Risk-Free Rate

### 🔗 2. `Binomial_Black_Scholes.ipynb` — Pricing Models Comparison

- Implements:
  - **Black-Scholes Formula** for European call/put options.
  - **Binomial Tree Model** for both European and American options.
- Compares prices from both models.
- Demonstrates step-by-step pricing tree construction.
- Visualizes option price vs underlying stock price, time steps, etc.

### 📝 3. `OptionsPS (1).ipynb` — Worked Out Examples & Problem Set

- Collection of solved problems and short case studies.
- Focuses on applications of options pricing and derivatives theory.
- Includes:
  - Black-Scholes formula usage
  - Greeks interpretation
  - Hedging strategy examples

## ✅ Features

- 📊 Graphical visualizations of option payoffs
- 🧠 Intuitive learning of pricing behavior
- 🔢 Mathematical pricing model implementations
- 📘 Practice problems with step-by-step solutions

---

## 🛠️ Requirements

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib scipy
