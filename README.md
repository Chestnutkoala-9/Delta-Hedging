# Delta-Hedging

This project aims to provide a framework for implementing and evaluating delta hedging strategies for financial derivatives. Delta hedging is a risk management technique used by traders and market makers to reduce or eliminate the directional risk of an options portfolio.

### Introduction
Delta hedging involves adjusting the portfolio's positions in the underlying asset to offset the changes in the value of the derivative contract. By continuously rebalancing the portfolio, traders can maintain a delta-neutral position and minimize their exposure to directional price movements.

### Method
This implementation follows a discrete-time simulation approach to manage the risk associated with financial derivatives. The methodology involves dynamically adjusting the portfolio's positions in the underlying asset to offset changes in the derivative's value due to underlying price movements. 

The steps can be summarized as follows:
- Delta Calculation: Calculate the delta of the options in the portfolio using the Black-Scholes-Merton (BMS) delta formula.
- Portfolio Rebalancing: Continuously rebalance the portfolio to maintain a delta-neutral position, minimizing exposure to directional price movements.
- Simulation of Price Movements: Simulate the underlying asset's price movements using a discrete-time model based on geometric Brownian motion.
- Performance Evaluation: Evaluate the performance of the delta hedging strategy by comparing the synthetic call option price with the actual call option's payoff.


