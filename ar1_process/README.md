<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: ar1_process

Published in: Stochastic processes

Description: Simulates the path of a First-order autoregressive (AR-1) process over 50 time points.

Epsilon terms/innovations are normally distributed - N(0,1). Model: X_t = 100 + r(X_t-1 - 100) + e_t. Mean reverting to 100, 0 < r < 1.

Keywords: autoregressive, normal-distribution, plot, random, random-number-generation, simulation, standard-normal, stochastic-process, time-series

See also: random_walk, randomwalk_ar1

Author: Lukas Borke

Submitted: Fri, May 29 2015 by Lukas Borke

Input: 
- N: number of simulated time points
- StartVal: Starting value for X_0
- rho: First AR-parameter (rho * X_t-1)

Example: 
- 1: Realized AR(1) path - number 1, rho = 0.8
- 2: Realized AR(1) path - number 2, rho = 0.8

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/Stochastic_processes/master/ar1_process/ar1_process-1.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/Stochastic_processes/master/ar1_process/ar1_process-2.png" alt="Image" />
</div>

