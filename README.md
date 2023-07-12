## Geometric Brownian Motion

"Volatility clustering" is a common phenomenon in financial markets that has been widely observed and studied. 

What are the facts ?

Large changes in asset prices (up or down) are likely to be followed by more large changes - and similarly for small changes. In other words, volatility, or the degree of variation of a trading price series over time, tends to cluster in periods.

This is of particular interest in the fields of asset pricing and risk management. 

For example :
    - if a stock's price has been highly volatile in the recent past, volatility clustering suggests that the stock's price is likely to continue to be highly volatile in the near future.
    - This is important information for traders and investors who need to manage their risk.

This phenomenon is not explained by simple models like the Geometric Brownian Motion model often used in finance, which assumes that returns are independently and identically distributed.

Question : What is the Geometric Brownian Motion model ?

The Geometric Brownian Motion (GBM) is a stochastic process often used in finance to model stock prices or other factors. 

It is characterized by two parameters:
    - the drift rate
    - the volatility

Mathematically, the GBM is typically described by the following stochastic differential equation:

$$
dSt​=μSt​dt+σSt​dWt​
$$

where:
    - $St​$ represents the stock price at time $t$
    - $dSt$ represents the infinitesimal change in the stock price at time $t$
    - $μ$ is the 'drift' rate, representing the average rate of return on the stock,
    - $dt$ represents an infinitesimal increment of time,
    - $σ$ is the 'volatility', representing the standard deviation of the stock's returns,
    - $dWt​$ represents a standard Wiener process (or Brownian motion), which is a random process with $dWt​∼N(0,dt)$


The main assumptions of GBM model:
    - The logarithmic returns of the stock price are normally distributed and independent of each other.
    - The mean and variance of the stock's return are constant over time.
    - The market is efficient, meaning that the stock price reflects all available information.

In reality, these assumptions are often violated to some degree. 

For example:
    - The returns of many financial assets exhibit 'volatility clustering', which contradicts the assumption of independent returns.
    - This is one reason why more complex models, such as the stochastic volatility models, are often used.
