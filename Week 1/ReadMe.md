# Week 1: Introduction to Stochastic Programming

## Introduction
Stochastic Programming is a mathematical framework for modelling optimization problems that involve uncertainity. Unlike deterministic programming which assumes perfect information, in stochatsic progamming, some or all of its problem parameters are uncertain, but follow known probability distributions as is common in real-world models and systems.

## Key Areas
Stochastic programming is mathematical (i.e.- linear, non-linear, integer optimization problems) and therefore contain the same elements present in deterministic models (i.e.- decision variables, objective function, constraints). The only difference being stochastic programming entails uncertainty.
  - **Decision Variables**- Represents the quantities to be optimized (maximized or minimized).The number of units to produce when managing inventory, the proportion of funds to invest when optimizing a portfolio of assets.
  - **Uncertainity**- This is modelled using scenarios each representing a possible future state of the world with an associated probability. For example:
      - Stock prices: Might rise, fall, or stay constant, with specific probabilities
      - Demand levels: Could be low, medium, or high, each with a likelihood
  - **Objective Function**- Due to the uncertainity present, it typically involves expected value optimization. We account for all possible uncertain scenarios and determine the best possible minimum or maximum of the function.
  - **Constraints**- They define the feasible region of the decsion variables. They can also be uncertain (probabilistic or chance constraints)

## The Two-Stage Stochastic Optimization Model (Recourse)
A decision-making framework that is divided into two stages:
  1. Make a decision
  2. We then see a realization of the stochastic elements of the problem but are then allowed to make further decisions to avoid the constraints of the problem from becoming infeasible (recourse).

### Example: Amount of Goods to Produce
Consider a simple manufacturing example. We have to make a decision about the amount of product X to produce. Each unit of X costs $10 to make. X is made to meet demand $(D)$ in the next time period but demand is stochastic, with a discrete probability distribution: $demand= D_s$ $P_s= (d= 1, \dots, S)$. Or rather, having $S$ scenarios for possible future demand.

Let's assume two scenarios:
  - demand > supply
  - demand < supply

We then have to decide how much to produce before demand is known. Say we produced 600 units. Once next period dmeand is realized, we need to decide how to manage shortages $(D_1= 700)$ or excess stock $(D_2= 500)$. This is known as recourse.

![Two-Stage](https://people.brunel.ac.uk/~mastjjb/jeb/or/STOCH1.GIF)

The recourse decision is implemented mathematically when an optimization model is formulated to minimize the expected penalty cost arising from both scenarios. 

## Tools
Python libraries such as CVXPY, NumPy, and Matplotlib are used to model, solve, and visualize stochastic optimization problems.
