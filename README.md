# 054361 - Metodi Analitici e Numerici per l'Ingegneria

A collection of modular `MATLAB` scripts implementing core numerical analysis algorithms for solving engineering problems.

<div align="center">
    <img src="./img/Cauchy-Dirichlet_problem.png" alt="Cauchy-Dirichlet Problem Solution" width="800"/>
    <br/>
    <figcaption>Numerical solution of a Cauchy-Dirichlet problem for a parabolic PDE using a non-complete Fourier Series expansion.</figcaption>
</div>


## Overview

The repository is structured to be simple and modular.
The `labs` directory contains the main lab scripts (`Lab*.m`), each corresponding to a specific topic or problem set.
The core logic is housed in the `functions/` directory, which contains a set of reusable `MATLAB` functions.

Key implemented algorithms include:
- **Root-finding:** Bisection, Newton's method, Fixed-point iteration.
- **Linear Systems:** Thomas algorithm for tridiagonal systems, Forward/Backward substitution.
- **Eigenvalue Problems:** Power method and Inverse power method.
- **Numerical Integration:** Composite Trapezoidal and Simpson's rules.
- **ODEs:** Euler (forward and backward), Heun, Crank-Nicolson, and a general Theta-method implementation.
- **PDEs/Finite Elements:** Solvers for diffusion and reaction-diffusion problems using Finite Element methods.
- **Iterative Methods:** Richardson, Gradient method.

The `img/` directory contains plots and diagrams generated from the lab scripts, visually representing the results of the simulations.


## Quick Start Guide

To run these scripts, you will need a working installation of `MATLAB` or `GNU Octave`.
Simply clone the repository and navigate to the `labs` directory to execute the lab scripts.

You will also need to add the `functions/` directory to your `MATLAB` path to ensure that all functions are accessible.

```bash
addpath('functions');
```


## Examples of Simulations

The scripts produce a variety of numerical solutions, often visualized as plots. Here are a couple of examples from the collection.

#### Satellite Trajectory Simulation

Numerical integration of a satellite trajectory under the influence of Earth's gravity and hypothetical air resistance.

<div align="center">
    <img src="./img/Satelite_trajectory.png" alt="Satellite Trajectory" width="600"/>
    <br>
    <figcaption>Simulation of the satellite trajectory approaching Earth</figcaption>
</div>

#### SEIR Model for Epidemic Spread

A simulation of a Susceptible-Exposed-Infected-Recovered (SEIR) model, a common model in epidemiology.

<div align="center">
    <img src="./img/SEIR_model.png" alt="SEIR Model" width="600"/>
    <br>
    <figcaption>SEIR model with a beta coefficient variable over time (the beta variable is the infection rate)</figcaption>
</div>

#### Galerkian Method Application

A simple application of the Galerkian method to a linear elastic element.

<div align="center">
    <img src="./img/Galerkian_application.png" alt="Galerkian_application" width="600"/>
    <br>
    <figcaption>Simple application of the Galerkian method to a linear elastic element</figcaption>
</div>

Have a nice coding day,

Tommaso :panda_face:
