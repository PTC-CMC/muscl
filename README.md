# sc-ff
A coarse-grained force field derived using the multi-state iterative Boltzmann inversion method (MSIBI) for simulating stratum corneum lipids .

##  Files
Tabulated non-bonded potentials can be found in the `nonbonded` directory. The directory contains a `.txt` file for each pair of atom types in the coarse-grained model. The `.txt` files are tab-separated tables in which the first column is the separation distance (*r*) in nm, the second column is potential energy (*V(r)*) in kJ/mol, and the third column is the force (*F(r)*) in kJ/mol-nm. 
