# Assignment 1 Overview - Phylogeny Reconstruction

## Background Info:
The project focused on phylogeny reconstruction—a technique traditionally used in systematic and evolutionary biology to understand life's evolutionary history on Earth. 
However, nowadays, this technique is gaining ground in other areas like comparative genomics and cancer biology, especially in understanding tumor progression. 

For this assignment, we used the Phangorn package in R.

## Objective
The primary aim is to apply practical methods to construct phylogeny using the Phangorn package in R, exploring both distance-based and Maximum Likelihood approaches to tree-building.

## The Data:
The data we worked with came from a study by Uddin et al. (2008) and included sequences of the COX5A gene from great apes, new and old world monkeys. 
The sequences, in FASTA format, weren’t aligned.

## The Process:
### Multiple Sequence Alignment (Task 1):
We aligned the COX5A sequences using the MUSCLE tool and reviewed the alignment, focusing on insertion/deletions in it.
### Building a Distance-Based Phylogeny (Task 2):
We built a phylogenetic tree from the multiple sequence alignment using distance methods, explored the JC69 correction, and compared JC69 distances to p-distances. 
We then constructed Neighbor-joining trees, performed bootstrapping, and explored various evolutionary concepts.
### Maximum Likelihood Analysis (Task 3):
Chose the best model of sequence evolution that suited our data and performed a Maximum Likelihood-based phylogeny reconstruction.

## Tools and Packages Used:
RStudio for interactive coding
Phangorn Package for phylogenetic analysis
ggtree and treeio for tree visualization and data handling
