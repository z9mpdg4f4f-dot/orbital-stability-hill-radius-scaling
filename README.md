# Orbital Stability and Hill Radius Scaling

This repository contains the computational model used in the study:

Orbital Stability and Gravitational Dominance Across Planetary Systems: A Hill-Radius Scaling Approach

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

orbital_stability_hill_radius_scaling.py  
Main simulation code.

figures/  
Generated plots used in the analysis.

paper/  
Published research paper.

## Notes

This model provides a simplified indicator of gravitational dominance. It does not solve the full restricted three-body problem and does not include time-dependent orbital integrations.

