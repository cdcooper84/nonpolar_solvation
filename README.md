## An implicit solvent model for nonpolar solvation

This repository contains code of an implementation of the implicit solvent model from "A simple electrostatic model for the hard-solute component of nonpolar solvation" (*submitted*), by C. D. Cooper and J. P. Bardhan.
The model uses a solute-shaped capacitor to compute the energy required to generate a cavity that fits the solute inside the solvent, and a boundary integral for the solute-solvent dispersion interaction energy.

The notebook in `nonpolar_energy.ipynb` reads in the Supplementary Information from Mobley et al (JCTC, 2009), and computes the nonpolar solvation free energy using our model. To run, you'll need:
 * [bempp](https://bempp.com/), version 3.4.3. Adaptation to the latest version (`bempp-cl`) is work in progress.
 * [ParmEd](https://parmed.github.io/ParmEd/html/index.html) (Available with `pip` or `conda`).
 * [msms](https://mgl.scripps.edu/people/sanner/html/msms_home.html). Adaptation to the Python version is work in progress.
 
The notebook `energy_plots.ipynb` reads in energies from `implicit_data.txt` and `explicit_data.txt` and plots them interactively with [`plotly`](https://plot.ly/) (available from `pip` or `conda`).
 
Let us know if you have any questions/comments/suggestions!
