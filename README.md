# GPU acceleration of CVODES for stiff integration of chemical kinetics

For numerical analysis of reaction flow, such as
combustion, a strong integration of a highly stiffed
chemical reaction system is required.
However, since the system grows proportionally to the
number of chemical species, significant computational
costs are incurred and an increase in computational
speed is essential to address this.
The methods used for accelerating calculations include
parallel processing using multiple processors of the
central processing unit (CPU), and parallel operation
using the graphics processing unit (GPU).

### Demonstration
This repo contains the following documents

1. Install cantera-magma in titanv manual.pdf  
This file demonstrates how to install CANTERA-magma based on GPU
2. Poster.pdf  
This file explains the experimental result about comparision between CPU and GPU acceleration spped for ignition test

### Environment
* OS: Ubuntu 14.04.4 LTS
* Used languages: C++