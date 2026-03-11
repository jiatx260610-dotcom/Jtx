# Origin of void swelling resistance in concentrated solid solution alloys revealed by self-adaptive accelerated molecular dynamics

This repository contains the input files, analysis scripts, and representative data associated with the manuscript:

## Overview

This repository provides materials for reproducing the simulations and analyses in our study on vacancy diffusion, aggregation, dissociation, and structural transformation in pure Ni and Ni-based concentrated solid solution alloys.

## Repository structure

- `SAAMD/`  
  Simulation input files, Representative atomic configurations, Python for data processing, structural identification, and figure generation for pure Ni and different CSAs via SAAMD.

- `ASD/`  
  Simulation input files and Python for data processing for ASD of pure Ni and different CSAs via LAMMPS.

- `Binding_energy/`  
  Simulation input files, Representative atomic configurations, Python for data processing, structural identification, and figure generation for Binding energy of pure Ni and different CSAs via LAMMPS.

- `NEB/`  
  Simulation input files, Representative atomic configurations, Python for data processing, structural identification, and figure generation for NEB of pure Ni and different CSAs via LAMMPS.

## Systems studied

The simulations include:

- Pure Ni
- NiCo
- NiFe
- NiCoFe
- NiCoFeCr
- NiCoFeCrMn

## Methods

Self-adaptive accelerated molecular dynamics was used to capture vacancy diffusion, aggregation, cluster dissociation, and structural transformation at experimentally relevant times.

More methodological details are provided in the manuscript and Supplementary Information.

## Requirements

Example environment:

- LAMMPS
- Python 3.8
- OVITO
- NumPy
- Matplotlib

## Data availability

Representative input files, processed data, and analysis scripts are provided in this repository. Additional simulation data are available from the corresponding author upon reasonable request.

## Code availability

The custom scripts used for data analysis and visualization are available in this repository. Additional implementation details of the self-adaptive accelerated molecular dynamics workflow are available from the corresponding author upon reasonable request.

## Citation

If you use this repository, please cite.

## Contact

For questions regarding the data or scripts, please contact:

- Tengfei Yang
- Hunan University
- yangtengfei@hnu.edu.cn

## License

This project is released under the MIT License / CC BY 4.0 / other applicable license.