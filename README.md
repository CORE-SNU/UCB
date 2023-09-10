# UCB
====================================================

This repository includes the MATLAB codes to perform the simulations in **[Data-Driven Stochastic Optimization Using Upper Confidence Bounds: Performance Guarantee and Distributional Robustness][paper_link]**.

## 1. Requirements
To run our codes without modification, the following softwares must be installed:
- **[MATLAB][MATLAB]**
- **[CPLEX Optimization Studio][CPLEX]**

which are free for students and academics. Regarding their versions, we used R2019a and 12.10, respectively. 

## 2. Simulations
The folder has two script files, each for one test problem used in the paper: 
`newsvendor.m` and `farm_management.m`.
By running a script file, you can compute the optimal values and the expected costs of each method, both averaged over `N_simu` (1000 by default) independent sample data sets, for a fixed sample size `N` (10 by default) and the 19 confidence levels.

[paper_link]: ..
[MATLAB]: https://matlab.mathworks.com
[CPLEX]: https://www.ibm.com/products/ilog-cplex-optimization-studio
