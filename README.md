# Ornstein-Uhlenbeck Process Simulation

This repository contains a simple Python implementation of the **Ornstein-Uhlenbeck (OU) process**, a type of mean-reverting stochastic process commonly used in physics, finance, and other fields.

## 📄 Description

The Ornstein-Uhlenbeck process is described by the stochastic differential equation:

\[
dx(t) = theta * (mu - x(t)) * dt + sigma * dW(t)
\]

where:
- \( \theta \) is the speed of reversion,
- \( \mu \) is the long-term mean,
- \( \sigma \) is the volatility,
- \( dW(t) \) is the increment of a Wiener process (Brownian motion).

This script simulates the OU process using the Euler–Maruyama method and plots the resulting time series.

## 📦 Dependencies

Make sure you have the following Python libraries installed:

- `numpy`
- `matplotlib`

Install them using pip if necessary:

```bash
pip install numpy matplotlib

🚀 How to Run

Run the script directly from your terminal or IDE:

python Ornstein-Uhlenbeck_process_implementation.py

This will:

    Simulate an Ornstein-Uhlenbeck process.

    Plot the generated path.

⚙️ Parameters

The following parameters are used in the simulation:
Parameter	Description	Default
dt	Time step size	0.1
theta	Speed of mean reversion	1.2
mu	Long-term mean	0.5
sigma	Volatility	0.3
n	Number of time steps	10,000

You can modify these values in the generate_process() function as needed.
📈 Output

The script will generate a plot showing the simulated Ornstein-Uhlenbeck process over time.
