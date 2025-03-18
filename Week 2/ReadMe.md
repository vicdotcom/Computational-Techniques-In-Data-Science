# Week 2: Random Walk

## Introduction
A random walk is a type of stochastic process where a variable takes steps randomly in some space (i.e.- time, position, value). It decsribes the current observation as equal to the previous observation plus a random change (i.e.- a random step up, down, left or right).

$$X_t= X_(t-1) + w_t$$

Where $w_t$ is a random step often drawn from a probability distribution. In time series, it could be described as _gaussian white noise_ if the random step follows a normal distribution.

Random Walks can be either discrete or continuous:
- **Discrete:** Where the variable moves in discrete steps (e.g.- [-1, +1]) with equal or unequal probability. Examples include daily stock price, a person randomly stepping left or right)
- **Continuous:** Where the process evolves continuously over time and the step size follows a normal distribution $W_t \sim N(0, \sigma^2)$. E.g.- Brownian motion.

## 1D and 2D Random Walk
### 1D Random Walk
Occurs when movement is restrivted to a single axis, i.e.- left or right along a plane. At each step, the walker moves left (-1) or right (+1) with equal probability (unbiased, no drift) or unequal probability (biased, with drift). A good example of this is daily stock price.

Mathermatically, the position at each step updates as:

$$X_{t+1}= x_t + w_t$$ 
$$w_t \in (-1, +1)$$

### 2D Random Walk
Allows movement in two perpendicular directions (i.e.- left and right; up and down). The position is defined as $(X_t, Y_t)$ with each step being:

$$(X_{t+1}), Y_{t+1}= (X_t + w_t, y_t + \epsilon_t)$$

Examples- Particle diffusion in physics, Brownian motion.
