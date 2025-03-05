# Economic-Modelling
Analyzing the Dynamics of an Economic Model with Exogenous Shocks


1. Introduction

This project delves into the intricate dynamics of an economic model that elucidates the interplay between consumption, capital accumulation, and technological shocks. The model, represented by a system of equations, captures the equilibrium relationships between key economic variables.    

2. Methodology

2.1 Model Calibration

The initial step involves calibrating the model by determining the values of key parameters.    
This calibration is achieved by numerically solving a system of four equations using a solver from the scipy.optimize toolbox in Python.    
The obtained parameter values ensure that the model accurately reflects the underlying economic relationships.    
2.2 Simulation of Shocks and Variable Dynamics

A sequence of random shocks is generated to simulate the exogenous technology process.    
The model is then employed to simulate the dynamic responses of consumption and capital to these shocks over a specified time horizon.    
The standard deviations and correlations of these variables with the technology process are calculated to assess their volatility and interdependencies.    
2.3 Impulse Response Analysis

The impulse response functions of consumption and capital to a one-time technology shock are plotted.    
This analysis helps visualize and understand the dynamic adjustments of the variables following a shock to the system.    
2.4 OLS Regression

Ordinary Least Squares (OLS) regression is performed on the simulated data to estimate the relationship between consumption, capital, and the technology process.    
The estimated coefficients are compared with the model's parameters to assess the consistency of the simulation results.    
3. Results and Discussion

The numerical solver successfully identified the parameter values, enabling accurate calibration of the model.    
The simulations revealed the dynamic responses of consumption and capital to technological shocks, highlighting their volatility and interdependencies.    
The impulse response analysis visualized the adjustments of the variables following a one-time shock, providing insights into the model's dynamics.    
The OLS regression results confirmed the consistency of the simulation results with the model's parameters.    
4. Conclusion

This project provides a comprehensive analysis of an economic model using numerical and statistical methods. The findings shed light on the dynamic interactions between consumption, capital accumulation, and technological shocks, contributing to a better understanding of economic fluctuations and growth. The Python code developed for this project enables further exploration and analysis of the model under different scenarios and assumptions.
