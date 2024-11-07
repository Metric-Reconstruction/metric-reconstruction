[![2403.20311](https://img.shields.io/badge/arXiv-2403.20311-b31b1b.svg)](https://arxiv.org/abs/2403.20311) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Metric-Reconstruction/metric-reconstruction/blob/main/LICENSE)
# Gravitational Waves on Kerr Black Holes #

A suite of Mathematica notebooks containing analytic expressions for the metric perturbations of a Kerr black hole.

## Notebook Descriptions

**MetricPerturbations.nb** 

This notebook provides analytic expressions for the metric perturbations of a Kerr black hole. The metric components are given in Boyer-Lindquist, ingoing, and outgoing coordinates and in two gauges: ingoing radiation gauge (IRG) and outgoing radiation gauge (ORG). These explicit expressions are saved in the directory `metric-perturbations/`.

_______
**EinsteinFieldEquations.nb** 

This notebook: 
1. Computes the linearized Einstein tensor associated with an arbitrary perturbation of the Kerr background and saves its components in the directory `linearized-Einstein-tensor/`. This step takes a few minutes of runtime on a laptop.
2. Imports the components of the metric perturbations from `MetricPerturbations.nb` and verifies that they solve the linearized Einstein vacuum equations. 

This check is carried out for both radiation gauges (IRG and ORG) but only in Boyer-Lindquist coordinates.  A simple coordinate transformation is then sufficient to establish correctness of the components in ingoing and outgoing coordinates.
_______
**ExampleUsage.nb** 

This notebook showcases how the explicit expressions from `MetricPerturbations.nb` can be used for symbolic or numeric computations. As an example, we display plots of metric perturbation components.

______________
R. Berens, T. Gravely, and A. Lupsasca, “Gravitational Waves on Kerr Black Holes I: Reconstruction of Linearized Metric Perturbations,” 2024. [arXiv:2403.20311](https://arxiv.org/abs/2403.20311)
______________
