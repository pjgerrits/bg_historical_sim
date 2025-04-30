# Mountain Moves: Spatial Interaction Modelling of Bulgaria’s Internal Migration (1934 – 1992)

This repository accompanies the paper:

**Mountain Moves: Spatial Interaction Modelling of Bulgaria’s Internal Migration (1934 – 1992)**  
**Authors:** Petrus J. Gerrits\*, Guy Solomon, M. Erdem Kabadayi, Ana Basiri  
\*Corresponding author: [p.gerrits.1@research.gla.ac.uk](mailto:p.gerrits.1@research.gla.ac.uk)

> **Zenodo DOI**: [insert DOI here]  
> [![DOI](https://zenodo.org/badge/DOI/INSERT_DOI_HERE.svg)](https://doi.org/INSERT_DOI_HERE)

---

## Abstract

This study provides a spatial analysis of internal migration in Bulgaria from 1934 to 1992. Using geocoded settlement-level census data and spatial interaction models (SIMs), we examine the impact of challenging topography on migration flows, showing how mountainous landscapes shaped movement and urban expansion during major socioeconomic shifts. By combining historical census records with modern geospatial methods, we expose local migration dynamics overlooked by broader-scale approaches. In a country that experienced dramatic rural decline alongside rapid urban growth, our findings supply essential historical context for contemporary policy debates and urban planning. The work offers a robust framework for understanding the interplay between landscape and migration dynamics.

---

## Keywords

Internal migration · population · spatial interaction model · historical data · census · human geography · geospatial analysis · rural depopulation · settlement-level analysis · topography · urbanisation · accessibility · Bulgaria

---

## Repository Structure

```text
calculated_distance_matrices/            ← Pre-computed origin–destination matrices
│   ├─ distance_matrix_bg_3.npz          Road-network distances between all settlements
│   └─ euclidean_distance_matrix.npz     Straight-line (Euclidean) distances
│
output_figures/                          ← Figures generated for the paper
│   ├─ Figure1.tif … Figure9.tif
│
scripts/                                 ← Reproducible Jupyter notebooks
│   ├─ 01_create_distance_matrix.ipynb   Build Euclidean & road matrices
│   ├─ 02_unconstrained_sim_analysis.ipynb
│   └─ 03_analysis_and_figures.ipynb     Analyse results & export figures
│
source_files/                            ← Raw input data
│   └─ bg_census_merged_data_pivot.xlsx  Settlement-level census data (1934-1992)
│
readme.md


