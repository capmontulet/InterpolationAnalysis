# InterpolationAnalysis



## Overview

This repository contains an R implementation of polynomial interpolation using the Lagrange method. The goal is to approximate a given discrete function using interpolation techniques and evaluate the function at specified points.

## Dataset

The given dataset represents the function with the following discrete values:

𝑓(𝑥) = cos0.5𝑥 × 𝑒<sup>0.1𝑥</sup> 

| 𝑥 | π | 6.678 | 3π | 12.961 | 5π | 19.244 | 7π |
| :---:         |     :---:      |          :---: | :---:         |     :---:      |          :---: |  :--: | :---: |
|  𝑓(𝑥)  | 0    | -1.921 | 0 | 3.584 | 0 | -6.718 | 0 |


## Features 

- Lagrange Interpolation: Computes the interpolating polynomial using Lagrange basis functions.

- Polynomial Calculation: Uses the poly.calc() function to derive the interpolating polynomial.

- Visualization: Plots each Lagrange basis polynomial separately and the final interpolating function in a 4x2 figure layout.

- Function Evaluation: Evaluates the interpolating polynomial at given points (e.g.,  and ).


## Output 

The L1 - L7 graphs show the Lagrange basis polynomials, each influencing the interpolation at specific data points. The p(x) graph represents the final interpolating polynomial.


![lagrange](https://github.com/user-attachments/assets/fbab70b9-5aa4-4441-aeb3-3daeb9869d3a)

