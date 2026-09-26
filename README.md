# Genetic_Drift_Simulation
This is a toy model of evolution, to see if vectors can (sort of) be used to simulate genetics.

This was originally to be a coding sandbox, but I turned it into a miniature math/science experiment, where they attempted to build a couple of mathematical models of evolution, in particular how genes can change over time. Vectors are used to simulate genomes, and the numbers are the 'genes.' 

- One model focuses on a single population changing over time, or as a simplified model of asexual reproduction. A single vector is modified, then the new vector is modified again, until a number of generations pass.
- The other model attempts to simulate the divergence of species, or sexual reproduction. Two vectors are passed through an algorithm that combines them and creates 4 new vectors of that family, which are then put back into the algorithm to keep the process going for a specified number of generations. The final result has 4 vectors: a male-1, female-1, and a male-2 and female-2, corresponding to the 1 and 2 families or species.
