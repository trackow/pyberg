# pyberg, a simple iceberg drift and decay model in Python
Routines and notebooks for computing iceberg trajectories and melting offline

- so far supports reading interpolated forcing data from COSMO and AWI-CM
- code is based on the Fortran code of FESOM-IB

The Fortran source can be found [here](https://github.com/trackow/iceberg-templates/blob/master/compute_iceberg_PDFs_sectorsLONLAT.ipynb). As a next step, the Weeks-Mellor rollover criterion and other details will be added.


**Pre-industrial test over 20 years**. Using COSMO input data.

![Pre-industrial case PI](./test.png)
