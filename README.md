# Protonate

Takes a `mol2` file and adds protons on specific atomtypes and outputs it in `xyz` format.

Currently protonates amine, imine, and aromatic Ns

## Usage

    ./protonate.py xxx.mol2 > xxx.xyz


## TODO

 - currently skips all N.pl3 atoms, but should protonate N.pl3 atoms bonded to only 2 atoms

