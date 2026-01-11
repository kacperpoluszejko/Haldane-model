# Haldane Model Simulation

Numerical simulation of the Haldane tight-binding model on a honeycomb lattice, demonstrating the quantum anomalous Hall effect (QAHE) in the absence of an external magnetic field.  
The project focuses on the computation of band structures, Berry curvature, and Chern numbers for topological phases.

## Methods
- Tight-binding Hamiltonian on a honeycomb lattice
- Berry curvature integration over the Brillouin zone
- Chern number calculation
- Finite ribbon geometry for edge-state analysis

## Technologies
- Python
- Kwant
- NumPy, SciPy
- Matplotlib

## Results
- Energy band structures for bulk and ribbon geometries
- Berry curvature distributions
- Topological phase characterization via Chern numbers

Example outputs are shown below.

![Band structure](images/ArmBand_3(1).png)  
![Berry curvature](images/ZigBand_3.png)

## How to run
The main results are generated in the Jupyter notebook:
```bash
jupyter notebook Haldane_graphene.ipynb


