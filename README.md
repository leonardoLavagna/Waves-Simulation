# Waves-Simulation

https://user-images.githubusercontent.com/91341004/161398820-759087b1-d4d8-41cb-8d44-19dfcdb45cbe.mov

The main goal of this project is to provide (in Python) a variety of tools to approach some problems related to wave equations (with applications mainly in seismology). In particular:
1) We will develop the finite-difference algorithms to simulate the **acoustic wave equation in 1D**, and how to initialize a simulation example. We will look at solutions using the Python implementation and observe numerical artifacts (dispersion and exploding solutions), then we will apply the CFL criterion to obtain a conditionally stable algorithm for explicit finite-difference schemes. An important tool we will use to toone our simulations will be the von Neumann Analysis. See **Notebook 5** and **Notebook 6**.
2) We will develop the solution to the **2D acoustic wave equation**, compare with analytical solutions and demonstrate the phenomenon of numerical (non-physical) anisotropy. We will extend the von Neumann Analysis to 2D and see how to initialize a realistic physical problem. In this context we will observe that 2D solution are already quite powerful to understand complex wave phenomena. 
3) We will introduced the **1D elastic wave equation** and use staggered-grid schemes with the coupled first-order velocity-stress formulation.
4) We will use the discrete Fourier series and highlight their exact interpolation properties on regular spatial grids. We will then introduce the derivative of functions using discrete Fourier transforms and use it to solve the 1D and **2D acoustic wave equation**.
5) The necessity to simulate **waves in limited areas** will lead us to use Chebyshev polynomials for function interpolation. We will then develop the concept of differentiation matrices and discuss a solution scheme for the elastic wave equation using Chebyshev polynomials.
6) We will look at the **weak form of the wave equation**, discussing the Galerkin principle and derive a finite-element algorithm for the static elasticity problem based upon linear basis functions. We will also see how to implement boundary conditions. The finite-difference based relaxation method will be derived for the same equation and the solution compared to the finite-element algorithm.
7) We will extend the **finite-element method** to the elastic wave equation and compare the solution scheme to the finite-difference method. We will also introduce the concept of h-adaptivity, the space-dependence of the element size for heterogeneous media.
8) We will use the **spectral-element method** to develop a solution scheme for the 1D elastic wave equation (with Lagrange polynomials as the basis functions of choice).
9) We finalize the derivation of the spectral-element solution to the elastic wave equation. We will then demonstrate the **numerical solution for homogenous and heterogeneous media**.

## Remark.
This project is still a working in progress. We will add all the material step by step as the project develops. 
