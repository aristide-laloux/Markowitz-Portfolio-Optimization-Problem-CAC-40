# CAC-40 Markowitz Portfolio Optimization Project

## Overview

This project explores and implements portfolio optimization strategies using the Markowitz framework on the CAC-40. The project is divided into three main parts:

The maths behind the optimization problem are done in the notebook

## Project Structure

- **Data Exploration and Estimation of the mean vector of returns and the covariance matrix of returns**:
  - Visualization of stock performances over different time horizons (daily, monthly and annual).
  - Data exploration and empirical estimation of the mean vector \( \mu \) and covariance matrix \( \Omega \) CAC-40 stock data.


- **Portfolio Optimization with Risk-Free Asset**:
  - Implementation of the Markowitz optimization problem including a risk-free asset.
  - Numerical solutions to the optimization problem, plotting the efficient frontier, and interpreting the results.

- **Portfolio Optimization without Risk-Free Asset (No ASR)**:
  - Implementation of the Markowitz optimization problem excluding a risk-free asset.
  - Numerical solutions to the optimization problem, plotting the efficient frontier, and analyzing the non-linear relationship between risk and return.

## Key Results

- **Efficient Frontier with Risk-Free Asset**:
  - The efficient frontier is linear, confirming the theory that with a risk-free asset, there is a direct and proportional relationship between risk and expected return.
  
- **Efficient Frontier without Risk-Free Asset**:
  - The efficient frontier is a half-parabola, highlighting the non-linear trade-off between risk and return in the absence of a risk-free asset.
  - The absence of feasible solutions for low-risk levels illustrates the intrinsic risk constraints of the market, making it impossible to achieve extremely low-risk portfolios.

## Conclusion

This project demonstrates the practical application of the Markowitz portfolio optimization theory to the CAC-40 index, providing insights into how portfolio optimization can be performed both with and without a risk-free asset. The findings align with theoretical expectations, showing the distinct differences in the efficient frontier when a risk-free asset is included versus when it is not.

This project serves as a comprehensive guide for implementing and understanding the Markowitz portfolio optimization in real-world stock markets.
