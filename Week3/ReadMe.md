# Week 3: Random Walk

## Intrduction
A random walk is a type of stochastic process where a variable takes steps randomly in some space (i.e.- time, position, value). It decsribes the current observation as equal to the previous observation plus a random change (i.e.- a random step up, down, left or right).

$$X_t= X_(t-1) + w_t$$
where $w_t$ is a rnadom step often drawn from a probability distribution. In time series, it could be described as _gaussian white noise_ if the random step follows a normal distribution.

Random Walks can be either discrete or continuous:
- **Discrete:** Where the variable moves in discrete steps (e.g.- [-1, +1]) with equal or unequal probability. Examples include daily stock price, a person randomly stepping left or right)
- **Continuous:** Where the process evolves continuously over time and the step size follows a normal distribution $W_t ~ N(0, \sigma^2)$. E.g.- Brownian motion.
