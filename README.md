# Nanoplastics from Molecular dynamics simulations
For the simulated annealing and standard molecular dynamics simulations, the Gromacs 2020.3 program was used, together with the CHARMM~36 force field to estimate the interactions between the atoms within the system.
For the polymers, force field parameters were obtained from the CGenFF web interface.
The leap-frog algorithm with a 1~fs timestep was used for integrating the equations of motion.
The temperature was controlled through a modified Berendsen thermostat, with a time constant of 100~fs.
The bonds involving hydrogen atoms were constrained through the simulations.
The particular workflow and the further settings of the simulations were subject to the present development, and therefore will be discussed in the main part of the paper.
