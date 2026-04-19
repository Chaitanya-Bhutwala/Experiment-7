Experiment 7: Polynomial Interpolation using Lagrange Method
Overview:

This experiment focuses on implementing Lagrange polynomial interpolation to estimate intermediate values from a given dataset. The objective is to study how interpolation order and point selection influence the accuracy and stability of the results.

Methodology:
Given dataset of x and f(x) values
Implementation of Lagrange interpolation for:
First-order (linear)
Second-order (quadratic)
Third-order (cubic)
Custom point selection strategy:
Fixed boundary points
Dynamic selection of intermediate points (forward/backward)
MATLAB-based computation of interpolated values
Handling numerical issues:
Avoiding duplicate nodes
Preventing division by zero and NaN values

Results:
First-order interpolation produced smoother but less accurate results
Second-order improved accuracy but showed some deviations
Third-order provided flexibility but was sensitive to point selection
Boundary values matched exactly with original data
Observed that accuracy depends more on point selection than polynomial order
Identified trade-off between higher-order interpolation and numerical stability
