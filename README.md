# pyberg, a simple iceberg drift and decay model in Python
Routines and notebooks for computing iceberg trajectories and melting offline

- so far supports reading (interpolated) forcing data from the COSMOS climate model and AWI-CM
- code is based on the Fortran code of FESOM-IB

The Fortran source can be found [here](https://swrepo1.awi.de/scm/viewvc.php/trunk/src/?root=fesom-ib), after registration at [swrepo1.awi.de](https://swrepo1.awi.de).


**Pre-industrial test over 20 years**. Using COSMO input data.

![Pre-industrial case PI](./PI_toXun.png)

**Last glacial maximum test over 20 years**. Using COSMO input data.

![Last glacial maximum test LGM](./LGM_toXun.png)
