---
layout: bio
datatype: project

title: "Creating a Modern Multiple Sequence Alignment and Filtering Workflow"
picture: "workflow_plots.png"
abstract: "Optimizing the QIIME workflow for multiple sequence alignment and positional filtering."
---

Microbiome surveys regularly make use of phylogenetic diversity metrics to examine community similarity. This requires the generation of a phylogenetic tree, which in turn requires the generation of a multiple sequence alignment. PyNAST is currently the most common approach for generating multiple sequence alignments for phylogenetic diversity calculations. Following PyNAST, a standard alignment mask (the “Lane mask” (Lane 1991)) is applied to filter non-phylogenetically informative positions (i.e., positions that vary at random, or which are nearly perfectly conserved). PyNAST employs heuristics that we know will result in errors in phylogenetic placement of some sequences. The “Lane mask” was generated when far less was known about bacterial diversity and needs to be updated based on more modern sequence collections.
We are performing a benchmark experiment to compare iterative and progressive multiple sequence alignment tools (Muscle, MAFFT, SSU-ALIGN) to PyNAST to identify an approach that that can be used as a replacement in the QIIME workflow. We are additionally comparing dynamic, entropy-based filtering to the traditional Lane mask-based filtering. We are using three data sets ranging from ~30,000 to ~360,000 sequences. All of these data sets were aligned and tests are being run on NAU’s High Performance Computing cluster, Monsoon.
.
