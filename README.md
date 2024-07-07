# Welcome to neuro-tutorials

Welcome to the Neuroimaging Tutorials repository! This repository provides comprehensive tutorials for neuroimaging analysis (including working with MRtrix, data quality checking for different MRI acquisition types, and more), sample codes, or links to other tutorials...

This project is under active development.

Neuroimaging Tutorials has its documentation hosted on **ReadTheDocs**.


## Table of Contents

- [Introduction](#introduction)
- [Tutorials](#tutorials)
  - [Data Quality Control](#data-quality-control)
  - [MRtrix](#mrtrix)
  - [TractSeg](#tractseg)
  - [Bundle Visualization](#bundle-visualization)

## Introduction

This repository contains a series of tutorials designed to help researchers and practitioners in the field of neuroimaging. The tutorials cover various aspects of neuroimaging analysis, with a particular focus on practical applications.

## Tutorials

### Data Quality Control

Ensure your data is of good quality for further processing with these tutorials.

- [Data Quality Control Overview](docs/data_qc.md)

### Working with DWI data

In the following guide, we will go through the following steps:

1. [Preprocessing (MRtrix)](#preprocessing-(mrtrix))
2. [Tractography(MRtrix)](#tractography-(mrtrix))
3. [Bundle segmentation (TractSeg)](#bundle-segmentation-(tractseg))
4. [Visualization of bundles](#visualization-of-bundles)

This guide was very much based the [Andy's Brain Book](https://andysbrainbook.readthedocs.io/en/latest/MRtrix/MRtrix_Course), the [MRtrix official documentation](https://mrtrix.readthedocs.io/en/3.0_rc1/reference/scripts/dwipreproc.html), the [B.A.T.M.A.N tutorial](https://osf.io/fkyht/wiki/home/) and the [TractSeg official documentation](https://github.com/MIC-DKFZ/TractSeg).

#### MRtrix

Learn how to work with MRtrix, a set of tools designed for the processing of diffusion MRI data.

- [MRtrix Overview](docs/mrtrix.md)
- [Preprocessing with MRtrix](docs/preproc_mrtrix.md)


#### TractSeg

Automate the segmentation of white matter tracts using TractSeg.

- [TractSeg Overview](docs/tractseg.md)

#### Bundle Visualization

Visualize fiber bundles effectively.

- [Bundle Visualization](docs/bundlevis.md)


