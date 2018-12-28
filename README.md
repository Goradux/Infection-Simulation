# Infection Simulation
This small project is a simulation of disease spread with a given set of parameters.
The program takes several inputs: size of a matrix (NxN), chance to spread the disease to the neighbor (in %), minimum and maximum lengths for the sickness period, chance to die (in %) and the placement for initial infected citizens.

While being sick, a citizen has a chance to spread the disease to its neighbors. Population is presented as a two dimensional array. An example:

1 0 0

0 1 2

9 9 2

Different numbers represent different states of citizens:

0 - healthy

1 - sick

2 - dead

9 - recovered (once recovered, a citizen can not get sick again)

When the simulation is complete, it shows what the population looks like. The program can provide some statistics based on the run, too.

#How to run
To run the simulation, clone the repository. Import it to an IDE, and run from there.
