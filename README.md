# MuSCL: Multistate Stratum Corneum Lipid force field
A coarse-grained (CG) force field derived using the multi-state iterative Boltzmann inversion method (MSIBI) for simulating stratum corneum lipids .

##  Files
Tabulated non-bonded potentials can be found in the `nonbonded` directory. The directory contains a `.txt` file for each pair of atom types in the coarse-grained model. The `.txt` files are tab-separated tables in which the first column is the separation distance (*r*) in nm, the second column is potential energy (*V(r)*) in kJ/mol, and the third column is the force (*F(r)*) in kJ/mol-nm. 

Harmonic bonded interaction parameters can be found in the `bonded` directory. Harmonic bonds are described in `bonds.txt` in which the first column of the tab-separated table is name of the bond (i.e. the atom types involved), the second column is the bond distance in nm, and the third column is the force constant in kJ/mol-nm^2. Similarly, harmonic angles are described in `angles.txt` where the first column is the angle name, the second column is the angle in degrees and the third column is the force constant in kJ/mol-rad^2.

## CG Mapping Scheme
Mapping schemes for CER NS C24, CHOL, and FFA C24 are shown below. Each circle corresponds to a CG bead, which represents the atoms encompassed by the circle. The CG beads are labled with their bead type. In  all cases, CG beads are spherically symmetric. Water is mapped such that four water molecules are represented by a single CG bead. 

![image](https://user-images.githubusercontent.com/33552857/151215266-00a58e0e-03e3-4023-bb62-b791f357620e.png)

