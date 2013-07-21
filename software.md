---
layout: page
title: Software
group: navigation
---
{% include JB/setup %}

I have extensive professional experience in software engineering in Matlab/Simulink, C/C++,
and Python for control-systems, data analysis, and simulation. Below are a couple of Matlab toolboxes I've developed:

### [stepalize](http://www.github.com/dnmiller/stepalize)
A robust method for building linear, time-invariant models from step
responses that can be used to accurately identify time constants of
high-order linear systems. 

- Identifies arbitrarily high-order models without numerical differentiation
  or deconvolution.
- Allows for model-order selection at run-time.
- Supports overshoot/undershoot constraints via quadratic programs.
- Supports eigenvalue constraints via semidefinite programs.

The meaty details and an interesting application can be found in the
forthcoming publication "Thermal Dynamical Identification of Light-Emitting
Diodes by Step-Based Realization and Convex Optimization," to appear in
_IEEE Transactions on Components, Packaging, and Manufacturing Technology_
sometime in the near future.

## [RBIS](http://www.github.com/dnmiller/rbis)
Some realization-based methods for building linear, time-invariant models
form arbitrary input-output data using some results from classical
realization theory. This is an implementation of most of the algorithms
found in my [thesis](https://dl.dropbox.com/u/31688552/Miller_Thesis.pdf).
