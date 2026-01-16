# Quant Finance Starter: Monte Carlo & Black-Scholes

This project is a Python-based introduction to Quantitative Finance concepts. It explores two foundational models used in financial engineering to price derivatives and simulate market behavior.

## 📊 Overview

The script (`monte_carlo.py`) performs two main tasks:
1.  **Black-Scholes Pricing:** Analytically calculates the fair value of a Call Option and its Delta (risk sensitivity).
2.  **Monte Carlo Simulation:** Uses Geometric Brownian Motion to simulate 50 random future price paths for a stock, visualizing the concept of stochastic processes.

## 🛠️ Technologies Used

* **Python 3.x**
* **NumPy:** For vectorization and random number generation.
* **SciPy:** For statistical functions (Cumulative Distribution Function).
* **Matplotlib:** For visualizing the "spaghetti plot" of price paths.

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/hilton26/quant-finance-learning.git](https://github.com/hilton26/quant-finance-learning.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install numpy scipy matplotlib
    ```
3.  **Run the script:**
    ```bash
    python monte_carlo.py
    ```

## 📉 Key Concepts

* **Delta ($\Delta$):** Represents the rate of change between the option's price and a $1 change in the underlying asset's price.
* **Stochastic Process:** The mathematical framework used to model the random behavior of assets over time.

---
*Created as part of my journey into Quantitative Finance.*