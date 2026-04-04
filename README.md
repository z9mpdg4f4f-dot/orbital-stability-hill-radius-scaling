# Orbital Stability and Hill Radius Scaling

Computational model for analyzing gravitational dominance in planetary systems using Hill-radius scaling.

"Orbital Stability and Gravitational Dominance Across Planetary Systems: A Hill-Radius Scaling Approach"
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19361215.svg)](https://doi.org/10.5281/zenodo.19361215)

## Author

Ömür Çarboğa  
2026

## Overview

This project investigates how gravitational dominance changes with distance from a celestial body. The analysis uses the Hill radius as a scaling parameter to compare gravitational environments across different Solar System bodies.

The model evaluates the ratio between the gravitational force exerted by a celestial body and the gravitational force exerted by the Sun.

The following systems are analyzed:

- Earth  
- Mars  
- Jupiter  
- Asteroid 101955 Bennu

## Method

The simulation computes the ratio

F_body / F_sun

using Newton's law of gravitation:

F = GM / r²

Distances are normalized by the Hill radius:

r / R_H

The simulation samples the interval:

0.01 ≤ r / R_H ≤ 2

using 2000 radial points.

The boundary of gravitational dominance is defined where

F_body / F_sun = 1.

## Repository Structure

## Repository Structure

simulation code/
  orbital_stability_hill_radius_scaling.py  
  orbital_stability_hill_radius_scaling.ipynb

paper/
  Orbital_Stability_Hill_Radius_Scaling.pdf

figures/
  hill_radius_comparison.png
  Earth_stability_plot.png
  Mars_stability_plot.png
  Jupiter_stability_plot.png
  Bennu_stability_plot.png
 
## Notes

This model provides a simplified indicator of gravitational dominance. It does not solve the full restricted three-body problem and does not include time-dependent orbital integrations.

