[![2403.20311](https://img.shields.io/badge/arXiv-2403.20311-b31b1b.svg)](https://arxiv.org/abs/2403.20311) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Metric-Reconstruction/metric-reconstruction/blob/main/LICENSE)
# Gravitational Waves on Kerr Black Holes #

A suite of mathematica notebooks generating and utilizing metric perturbations about a Kerr black hole.

## Notebook Descriptions

**Metric Perturbation.nb** 
This notebook generates metric perturbations in Boyer-Lindquist (BL), ingoing, and outgoing coordinates in both the ingoing radiation gauge (IRG) and the outgoing radiation gauge (ORG) for each coordinate system. The end results are written to files located in the directory `metric-perturbations/`.

_______
**Einstein Checks.nb** 
This notebook: 
1. Computes the linearized Einstein tensor in a Kerr background.
2. Imports the results of `Metric Perturbation.nb` and verifies that the generated metric perturbations solve the linearized Einstein vacuum equations.

_______
**Example Usage.nb** 
This notebook showcases how one can import the results of `Metric Perturbation.nb` to be utilized for symbolic or numeric computations. In particular, it generates a numerical plot of a metric perturbation component.

______________
R. Berens, T. Gravely, and A. Lupsasca, “Gravitational Waves on Kerr Black Holes I: Reconstruction of Linearized Metric Perturbations,” 2024. [arxiv:2403.20311](https://arxiv.org/abs/2403.20311)
______________
