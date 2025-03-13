# Computational Techniques In Data Science
This repository documents the implementations, experiments and insights gained in the Computational Techniques in Data Science unit as part of my MSc in Data Science. Computational techniques entail modelling stochastic processes which will be done mostly in Python.

A stochastic process is a mathematical model of systems or phenomena that are uncertain and appear to vary in a random manner over time. Because of their random-like nature, its variables are not known with certainty but rather are associated with probability distributions. This means that we cannot predict the exact value of the variable, but we can estimate its likelihood uisng computational techniques such as optimization, simulation, and so on...

### Prerequisite: Deterministic Optimization
Performing linear and non-linear optimization via SciPy and CvxPy libraries in Python. This is just to get familiar with the optimization libraries in Python....and also optimization when all variables are known with certainity (deterministic processes)

The rest of course content is as follows:

| Week | Topics | Content |
|------|--------|---------|
|![Week 1](https://github.com/vicdotcom/Computational-Techniques-In-Data-Science/tree/main/Week%201) | Introduction to Stochastic Programming | Stochastic programming, Role of Uncertainty in Decision-Making Models, Applications in Finance, Logistics, and Healthcare. **PYTHON** (numpy and cvxpy packages) |
| Week 2 | Introduction to Random Walks | Definition of random walk, 1D & 2D Random Walks. **PYTHON** (numpy and matplotlib.pyplot packages) |
| Week 3 | Introduction to Linear Optimization Problems | Optimizing a linear objective function with constraints. **Python Implementation**: Using scipy.optimize.linprog |
| Week 4 | Introduction to Graph-theoretic Models | Graph Representation: Adjacency Matrix/List. Applications: Social networks, road maps, shortest paths. **Python Implementation**: Using networkx |
| Week 5 | Introduction to Stochastic Thinking | Stochastic vs Deterministic Models. Real-life Examples: Queueing systems, stock price modeling. **Python Example**: Simulating stochastic demand in a warehouse |
| Week 6 | Simple applications in solving linear problems | Examples: Production scheduling, Transportation problems. **Python Example**: Transportation problem using pulp |
| Week 7 | Programming: Fibonacci Numbers, Longest Increasing Subsequence, Knapsack Problem | Different aspects of Fibonacci Sequence. Knapsack Problem (Dynamic Programming) |
| Week 8 | DEA (Data Envelopment Analysis) | A method for efficiency measurement. **Python Implementation**: Using pyDEA |
| Week 9 | Monte Carlo Simulation in Data Science | Repeated random sampling for approximating distributions. Estimating Pi |
| Week 10 | Formulation, Geometry & Algorithms | Convex Optimization Concepts. Algorithms: Gradient Descent, Simplex. **Python Example**: Simplex Method with scipy.optimize |
| Week 11 | Defining Linear Programming problems | Mathematical Form: Maximize/Minimize: $c^T x$, Subject to: $Ax ≤ b, x ≥ 0$. **Python Example**: Using pulp |
| Week 12 | Introduction to Integer Linear Programming (IP) | LP where variables are restricted to integer values. **Python Example**: Using pulp |
| Week 13 | Optimization Problems, Dynamic Programming | Shortest Path Problem. Inventory Management. **Python Example**: Solving Shortest Path Problem with Dijkstra’s Algorithm |
