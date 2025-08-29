---
layout: post
title: ANSYS Vortex Shedding of Flow Over A Cylinder
description:  Simulated unsteady laminar flow over a 2D circular cylinder at a Reynolds number of 150 using ANSYS Fluent. Created the computational geometry and mesh, applied appropriate boundary conditions, and ran transient simulations to capture vortex shedding patterns. Generated velocity, pressure, and streamline plots along with Q-criterion visualizations to study wake dynamics. Calculated drag force and drag coefficient, and compared CFD results with experimental correlations to validate accuracy.
skills:
- ANSYS
- CFD
- Mesh Generation
- PISO & SIMPLE Numerical Methods
- Problem Solving
main-image: /ansys_1.png
## Geometry & Mesh
- Created a 2D domain with a circular cylinder in the center.
- Meshed it finely near the cylinder using inflation layers to capture boundary layer effects.
## Boundary Conditions
- Inlet: uniform velocity of 1 m/s.
- Outlet: pressure outlet (0 Pa).
- Top/Bottom: symmetry boundaries.
- Cylinder: no-slip wall.
---
