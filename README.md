Finite Element Analysis of a 1D Rod


Overview

This project implements a Finite Element Method (FEM) solution for a 1D rod under a uniform distributed load. The program assembles the global stiffness matrix and load vector, applies boundary conditions, and solves for nodal displacements using the Thomas algorithm for tridiagonal systems.


Features :

->Uses the Thomas algorithm to efficiently solve the tridiagonal system.
->Assembles global stiffness and load matrices for a 1D rod.
->Computes nodal displacements, strains, and stresses.
->Visualizes results using Matplotlib.


Dependencies :

This script requires the following Python libraries:
numpy
matplotlib

You can install the required dependencies using :
pip install numpy matplotlib


The script will output the nodal displacements and plot:

Displacement vs. x
Strain vs. x
Stress vs. x


Input Parameters :

N: Number of nodes (default: 100)
E: Young's modulus (default: 200 GPa)
A: Cross-sectional area (default: 0.01 m²)
L: Length of the rod (default: 1.0 m)
f: Uniform distributed load (default: 1000 N/m)

