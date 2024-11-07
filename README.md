# Enhanced Black-Scholes and Monte Carlo Models for Dynamic Option Pricing and Risk
robust framework for option pricing, dynamic hedging, and risk management using the Black-Scholes model and Monte Carlo simulations.

## Project Overview
This project implements a robust framework for option pricing, dynamic hedging, and risk management using the Black-Scholes model and Monte Carlo simulations. It uses real-time market data from Yahoo Finance to improve pricing accuracy, implement delta-neutral hedging strategies, and calculate Value at Risk (VaR) for a portfolio.

## Goals
- Accurate Option Pricing: Calculate fair prices for European call options using Black-Scholes and Monte Carlo methods.
- Dynamic Hedging Simulation: Implement a delta-neutral hedging strategy to manage portfolio risk.
- Risk Assessment: Estimate Value at Risk (VaR) to quantify the potential downside of the portfolio in extreme market conditions.

## Key Contributions
1. Realistic Option Pricing: Utilizes real-time volatility and drift parameters from Yahoo Finance to calculate theoretical option prices.
2. Dynamic Hedging: Adjusts portfolio positions based on Delta to maintain a delta-neutral position.
3. Value at Risk (VaR) Calculation: Computes 95% VaR to assess potential losses under extreme scenarios, providing a measure of downside risk.
4. Visualization: Displays sample price paths and distribution of ending portfolio values to illustrate risk exposure.

## Results
- Black-Scholes call price: 45.34; Monte Carlo call price: 45.29, showing strong alignment and pricing accuracy.
- 95% VaR: 23.68, indicating the potential worst-case portfolio loss with 95% confidence.
- Visualization of simulated price paths and portfolio value distribution, demonstrating hedging performance and risk levels.

## Key Components
1. Black-Scholes Model: Calculates the theoretical price of a European option using real-time volatility and drift parameters.
2. Monte Carlo Simulation: Simulates thousands of potential price paths for the underlying asset to calculate the average option payoff.
3. Dynamic Hedging Simulation: Implements a delta-neutral hedging strategy by adjusting the hedge based on Delta at each time step.
4. Value at Risk (VaR): Calculates the potential maximum loss at a 95% confidence level.
5. Visualization: Displays sample simulated price paths and distribution of ending portfolio values.
   
## Example Output
- Black-Scholes Call Price: 45.34
- Monte Carlo Call Price: 45.29
- 95% VaR: 23.68

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
