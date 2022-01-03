# sc-ff
A coarse-grained force field derived using the multi-state iterative Boltzmann inversion method (MSIBI) for simulating stratum corneum lipids .

##  Files
Tabulated non-bonded potentials can be found in the `nonbonded` directory. The directory contains a `.txt` file for each pair of atom types in the coarse-grained model. The `.txt` files are tab-separated tables in which the first column is the separation distance (*r*) in nm, the second column is potential energy (*V(r)*) in kJ/mol, and the third column is the force (*F(r)*) in kJ/mol-nm. 

Harmonic bonded interaction parameters can be found in the `bonded` directory. Harmonic bonds are described in `bonds.txt` in which the first column of the tab-separated table is name of the bond (i.e. the atom types involved), the second column is the bond distance in nm, and the third column is the force constant in kJ/mol-nm^2. Similarly, harmonic angles are described in `angles.txt` where the first column is the angle name, the second column is the angle in degrees and the third column is the force constant in kJ/mol-rad^2.
