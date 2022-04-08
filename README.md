# Waves-Simulation


https://user-images.githubusercontent.com/91341004/162207095-119297ef-a68c-4d2c-9df2-579d18c4737d.mov


The main goal of this project is to provide (in Python) a variety of tools to approach some problems related to wave equations (with applications mainly in seismology). The projects is divided into different parts:
- **Part_1** deals with the *acoustic wave equation in 1D*. In this part we will implement (in Python) reliable *finite difference methods* to simulate the solutions while trying to reduce numerical artifacts.
- **Part_2** working in progress...
- ...

## Updates
- **Apr. 1, 2022** Project start. 
- **Apr. 5, 2022:** Part 1 of the project is completed except for Notebook 1 we are still writing (it is not unlikely that the first notebook will be the last we will upload ^.^). 
- **Apr. 7, 2022:** Part 1 of the project has been inspected and some minor errors have been corrected. Part 1 is composed by Notebooks 1,2,3,4,5,6 and is made available in a single folder (where Notebook 1 is empty because we still have to write it...).

## Planning

1) We will develop the finite-difference algorithms to simulate the **acoustic wave equation in 1D**, and how to initialize a simulation example. We will look at solutions using the Python implementation and observe numerical artifacts (dispersion and exploding solutions), then we will apply the CFL criterion to obtain a conditionally stable algorithm for explicit finite-difference schemes. An important tool we will use to tune our simulations will be the von Neumann Analysis. 
2) We will develop the solution to the **2D acoustic wave equation**, compare with analytical solutions and demonstrate the phenomenon of numerical (non-physical) anisotropy. We will extend the von Neumann Analysis to 2D and see how to initialize a realistic physical problem. In this context we will observe that 2D solution are already quite powerful to understand complex wave phenomena. 
3) We will introduced the **1D elastic wave equation** and use staggered-grid schemes with the coupled first-order velocity-stress formulation.
4) We will use the discrete Fourier series and highlight their exact interpolation properties on regular spatial grids. We will then introduce the derivative of functions using discrete Fourier transforms and use it to solve the 1D and **2D acoustic wave equation**.
5) The necessity to simulate **waves in limited areas** will lead us to use Chebyshev polynomials for function interpolation. We will then develop the concept of differentiation matrices and discuss a solution scheme for the elastic wave equation using Chebyshev polynomials.
6) We will look at the **weak form of the wave equation**, discussing the Galerkin principle and derive a finite-element algorithm for the static elasticity problem based upon linear basis functions. We will also see how to implement boundary conditions. The finite-difference based relaxation method will be derived for the same equation and the solution compared to the finite-element algorithm.
7) We will extend the **finite-element method** to the elastic wave equation and compare the solution scheme to the finite-difference method. We will also introduce the concept of h-adaptivity, the space-dependence of the element size for heterogeneous media.
8) We will use the **spectral-element method** to develop a solution scheme for the 1D elastic wave equation (with Lagrange polynomials as the basis functions of choice).
9) We finalize the derivation of the spectral-element solution to the elastic wave equation. We will then demonstrate the **numerical solution for homogenous and heterogeneous media**.

This project is still a working in progress. We will add all the material step by step as the project develops. 
