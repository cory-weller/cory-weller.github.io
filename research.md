---
layout: default
title: Cory Weller | Research
---

For more detail, you can always check out my [CV](assets/docs/CAWeller_CV.pdf)!

# Research

<center><img src="/assets/img/Dros_58.jpg" height="210" width="300"></center>
<center>Bergland labbies at the 2017 Fly Meeting in San Diego</center>

## My Projects

### Reconstructing whole genomes from ultra-sparse data

### Computational tricks for efficiently simulating thousands of GWAS

### Uncovering the genetic basis of of desiccation tolerance in *Drosophila melanogaster*

### Studying the effect of bacteria spore-formation on evolutionary rate

### Evaluating a candidate SNP's effect on desiccation tolerance
Collaborator: Warren Wheaton, an undergraduate who majored in Biology and Economics.
Warren parsed preliminary GWAS results and selected a candidate SNP that appears to be associated with desiccation tolerance. Then, he generated two F5 hybrid swarm populations from multiple inbred lines: one hybrid swarm was fixed for the reference allele of the candidate SNP, and the second was fixed for the alternate allele. We measured survivorship every two hours until all flies died four days later, and discovered a highly significant difference in median survival time between the groups.

### Translating the genome reconstruction pipeline to an open-source framework
Collaborators: Ian Rector and Joseph Outten, two undergraduates double-majoring in Biology and Computer Science. As it currently stands, parts of my genome reconstruction pipeline rely on software that is not easily distributable, due to either being licensed software, or extremely difficult to compile. Ian and Joseph are working to implement these parts of the pipeline in an open-source framework using the Julia language. In particular, they are working towards an efficient implementation of the Viterbi algorithm that can interface with standard `.VCF` files. Their implementation is necessary for an open-source and computationally efficient method of identifying the most likely hidden states (haplotype combinations) while traversing a graph representing a recombinant individual with low-coverage sequencing data.
