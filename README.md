# Monte Carlo Option Pricing

This project simulates the price of a **European call option** using Monte Carlo simulation and compares it to the **Black–Scholes analytical price**. It demonstrates how the Monte Carlo estimate converges to the theoretical price as the number of simulations increases.

---

## Parameters

- **S0** = 100 (Initial stock price)  
- **K** = 100 (Strike price)  
- **r** = 0.05 (Risk-free interest rate)  
- **σ** = 0.2 (Volatility)  
- **T** = 1 (Time to maturity in years)  
- **N** = 100,000 (Number of Monte Carlo simulations)

---

## How to Run

1. Install dependencies:  
```bash
pip install numpy scipy matplotlib
```

2. Run the notebook:
```bash
jupyter notebook option_pricer.ipynb
```

3. Or run the script:
```bash
python option_pricer.py
```

---

## Results

Example output:

Monte Carlo Price: 10.47
Black-Scholes Price: 10.45

- As the number of simulations increases, the Monte Carlo estimate approaches the Black–Scholes price.  
- Convergence can be visualized in a plot of Monte Carlo estimate versus number of simulations.

---

## Concepts Demonstrated

- Monte Carlo simulation  
- Geometric Brownian motion  
- Risk-neutral option pricing  
- Python programming using NumPy and Matplotlib

---

## Author

Ben Whitehead
