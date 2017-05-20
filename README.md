# genetic-drift
A function to simulate genetic drift in a population using R.

Author: David Kradolfer, May 2017

This script defines a fuction to simulate genetic drift. Genetic drift describes the random fluctuation of allele frequencies in a finite size population. The frequency of ONE gene with TWO allels (0 and 1) is described. It is assuemed that organisms are HAPLOID (have only 1 allele per gene) and mate randomly. This means that if e.g. the frequency of allele 1 is 70%, then each individual in the next generation has a probability of 70% to inherit allele 1, and 30% to inherit allele 0. In small populations, genetic drift can cause alleles to disappear completely and thereby reduce genetic variation. This can be simulated using the function visGenDrift and setting the different parameters:

N = the population size (remains constant during the simulation)

numGen = the number of generations studied

numRep = the number of replicate simulations (maximum of 11)

p0 = initial frequency of allele 1
