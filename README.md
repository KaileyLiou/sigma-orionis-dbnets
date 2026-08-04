# Sigma Orionis DBNets Analysis

<!-- POSTER IMAGE -->

This repository contains the analysis and visualization code used to evaluate the applicability of DBNets2.0 to the σ Orionis star-forming region.

Using the published DBNets2.0 framework, we analyzed candidate gaps identified in σ Orionis disks and compared the inferred planet and disk properties with the published DBNets2.0 population. The goal of this project was to investigate whether DBNets2.0 can produce consistent predictions for a more distant star-forming region than those previously studied.

This work was completed as part of the Columbia ENG Foundations of Research program under the guidance of Dr. Jane Huang.

## Project Overview

- Applied DBNets2.0 to σ Orionis protoplanetary disks.
- Analyzed 11 candidate gaps.
- Compared inferred properties with the published DBNets2.0 population.
- Generated the figures used in our research poster.

## Background

Protoplanetary disks are disks of gas and dust surrounding young stars where planets form. As planets grow, they create gaps and rings within the surrounding disk. Because these young planets are often hidden within the dust, they cannot always be directly observed.

DBNets2.0 is a deep learning model that estimates hidden planet properties from observed disk structures. Previous work primarily focused on nearby star-forming regions, leaving it unclear whether the model can be applied to more distant systems. This project investigates whether DBNets2.0 can be successfully applied to the σ Orionis star-forming region by comparing the inferred planet and disk properties with the published DBNets2.0 population.

## Methodology

The workflow for this project consisted of the following steps:

1. Collected published DBNets2.0 comparison data from the supplementary materials of the original paper.
2. Created formatted CSV files containing the published planet and disk properties.
3. Applied DBNets2.0 to selected σ Orionis candidate gaps.
4. Recorded the predicted quantities, along with their associated uncertainties and confidence scores:
   - Planet mass
   - Orbital distance
   - Disk aspect ratio
   - Viscosity parameter
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

<img width="800" alt="plot_1_mp" src="https://github.com/user-attachments/assets/c097d0cb-eab9-4e0a-886d-f68e7dbfbbb6" />

*Figure 1. Comparison of predicted σ Orionis planet masses with the published DBNets2.0 population.*

## Requirements

- Python 3.x
- pandas
- matplotlib
- numpy

Install the required packages with:

```
pip install pandas matplotlib numpy
```

## Running the Analysis

1. Install the required Python packages.
2. Update the file paths in the notebook to match your local directory.
3. Run the notebook from top to bottom.

The notebooks will generate the comparison figures used in the research poster.

## References

This project uses published data from:
- A. Ruzza, G. Lodato, G. P. Rosotti, and P. J. Armitage, “DBNets2.0: Simulation-based inference for planet-induced dust substructures in protoplanetary discs,” Astronomy & Astrophysics, vol. 700, p. A190, Aug. 2025.
- J. Huang et al., “High-resolution ALMA Observations of Richly Structured Protoplanetary Disks in σ Orionis,” The Astrophysical Journal, vol. 976, no. 1, p. 132, Nov. 2024.

## Research Poster

The final research poster and abstract are available below.

<!-- [Research Poster (PDF)](...)
[Abstract (PDF)](...) -->

## Acknowledgements

This work was completed as part of the Columbia Engineering Foundations of Research program under the guidance of Dr. Jane Huang. We acknowledge funding from NSF AST-2307916.
