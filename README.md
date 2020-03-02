## An implicit solvent model for nonpolar solvation

This repository contains code of an implementation of the implicit solvent model from "A simple electrostatic model for the hard-solute component of nonpolar solvation" (*submitted*), by C. D. Cooper and J. P. Bardhan.
The model uses a solute-shaped capacitor to compute the energy required to generate a cavity that fits the solute inside the solvent, and a boundary integral for the solute-solvent dispersion interaction energy.

Codes are developed using the [bempp](https://bempp.com/) library, version 3.4.3. 
The latest version of bempp, called bempp-cl 0.1.1, does not work with the current code, its adaptation is work-in-progress.

Let us know if you have any questions/comments/suggestions!
