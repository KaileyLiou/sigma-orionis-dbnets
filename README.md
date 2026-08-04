# Sigma Orionis DBNets Analysis

This repository contains the analysis and visualization code used to evaluate the applicability of DBNets2.0 to protoplanetary disks in the σ Orionis star-forming region.

Using the published DBNets2.0 framework, we analyzed candidate gaps identified in σ Orionis disks and compared the inferred planet and disk properties with the published DBNets2.0 population. The goal of this project was to investigate whether DBNets2.0 can produce consistent predictions for a more distant star-forming region than those previously studied.

This work was completed as part of a research project under the guidance of Dr. Jane Huang.

## Background

Protoplanetary disks are disks of gas and dust surrounding young stars where planets form. As planets grow, they create gaps and rings within the surrounding disk. Because these young planets are often hidden within the dust, they cannot always be directly observed.

DBNets2.0 is a deep learning model that estimates hidden planet properties from observed disk structures. Previous work primarily focused on nearby star-forming regions. This project explores whether the same methodology can be extended to the more distant σ Orionis region.

## Project Objectives

The project focused on three primary goals:
- Apply the published DBNets2.0 model to candidate gaps identified in σ Orionis disks.
- Compare the inferred planet and disk properties with the published DBNets2.0 population.
- Evaluate whether the model produces consistent predictions for a more distant star-forming region.

## Methodology

The workflow for this project consisted of the following steps:

1. Collected published DBNets2.0 comparison data from the supplementary materials of the original paper.
2. Created formatted CSV files containing the published planet and disk properties.
3. Applied DBNets2.0 to selected Σ Orionis candidate gaps.
4. Recorded the predicted quantities along with the associated uncertainties and confidence scores.
- planet mass
- orbital distance
- disk aspect ratio
- viscosity parameter
- Stokes number
5. Reproduced comparison figures using Matplotlib.
6. Compared σ Orionis predictions with the published DBNets2.0 population.

## Figures

The repository includes scripts used to generate comparison plots for:
- Planet mass vs. orbital distance
- Disk aspect ratio
- Viscosity parameter
- Stokes number

These figures compare:
- published DBNets2.0 results
- σ Orionis predictions
- Solar System planets (for the planet mass comparison)

## Sources

This project uses published data from:
- A. Ruzza, G. Lodato, G. P. Rosotti, and P. J. Armitage, “DBNets2.0: Simulation-based inference for planet-induced dust substructures in protoplanetary discs,” Astronomy & Astrophysics, vol. 700, p. A190, Aug. 2025.
- J. Huang et al., “High-resolution ALMA Observations of Richly Structured Protoplanetary Disks in σ Orionis,” The Astrophysical Journal, vol. 976, no. 1, p. 132, Nov. 2024.

## Poster

The final research poster used to present this project will be included in the poster/ directory.

## Acknowledgements

This research was conducted under the guidance of Dr. Jane Huang.

We acknowledge funding from NSF AST-2307916.
