# Linear Programming

## Introduction
Linear Programming is defined as a linear function of a number of variables to be optimized (maximized or minimized), when such variables are subject to a number of constraints in the mathematical linear equalities ot inequalities. 

In short, it is a mathematical optimization technique used to maximize or minimize a linear objective function, subject to linear equality and inequality constraints. It is commonly used in resource allocation, production planning, transportation problems, and portfolio optimization.

## General Formulation
The goal of LP is to optimize (maximize or minimize) an objective function of the form:

$$Z= c_1x_1 + c_2x_2 + \dots + c_nx_n$$

where $z$ is the objective function, $c_i$ are the coefficients and $x_i$ are the decision variables.

The above objective function is subject to constraints which are linear equations or inequalities that limit the feasible region. 

$$A_x \leq b$$
$$A_x = b$$ 

Where $A$ is the matrix of coeffiecients, $x$ is the vector of decision variables, and $b$ is the vector of constraints.

## The Feasible Region & Optimal Solution
The feasible region is defined as the set of all possible solutions that satisfy the constraints of the problem. If a set of variables satisy the stated constraints, then a feasible region from—which the optimal solution can be be determined—exists.
![FeasibleRegion](https://www.researchgate.net/figure/Feasible-region-gray-colored-region-and-non-feasible-region-are-defined-by-a-set-of_fig3_266220942)

Once the feasible region is determined, the optimal solution is then computed. It is the best solution (the global minimum or global maximum) from the feasible solutions.
![OptimalSolution](https://www.solver.com/sites/default/files/local-global75.jpg)

