# Prob-Stats-Fundamentals-Bias-Variance


# Blood Pressure Analysis (cardio.csv)

This project analyzes the systolic blood pressure (`ap_hi`) from the `cardio.csv` dataset using statistical techniques.

## Tasks

### (a) Bias and Variance Analysis
- Randomly sample subsets of the dataset ranging from **0.1% to 99.9%**.
- Compute and plot **bias** and **variance** of the sample mean as a function of sample size.
- Interpret the observed trends.

### (b) Monte Carlo Simulations & Chebyshev Bound
- Approximate the probability that `ap_hi` deviates from the population mean using **Monte Carlo simulations**.
- Compare the empirical probability with the **Chebyshev inequality** bound.
- Validate insights related to the **law of large numbers**.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Usage
1. Load the dataset (`cardio.csv`).
2. Run the main.ipynb script to generate bias-variance plots.
3. Perform Monte Carlo simulations and compare with Chebyshev bounds.

