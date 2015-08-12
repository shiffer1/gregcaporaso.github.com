---
layout: bio
datatype: bio

title: Arron Shiffer
picture: "arron-shiffer/profile.png"
abstract: >
  I am a PhD student in Dr. Caporaso's lab. I am currently working on some benchmarking studies looking at four different multiple sequence aligners with "Lane mask" filtering vs strictly entropy based positional alignment filtering.
---


# Background
My background is primarily in Physics. I have an M.S. in Physics from University of California, Riverside
and a B.S. in Physics from Northern Arizona University. In addition, I have a B.S in Astronomy and a B.A. in
Philosophy from NAU.

# Interests

I am currently working on benchmarking studies looking at four different multiple sequence aligners (MUSCLE, MAFFT, PyNAST, and SSU-ALIGN). Each of these is being coupled with either Lane mask or strictly entropy based positional alignment filtering using scikit-bio. We are looking to find out if the phylogenetic trees and diversity results are as good or better than the use of PyNAST multiple
sequence alignment with Lane mask positional alignment filtering. We are creating many trees from the different workflows using FastTree. We then apply a Robinson-Foulds distance metric on those trees using scikit-bio to get a "distance" (A measure of similarity) from one tree to another. Using this distance we can see how closely we correlate to the current workflow. Additionally, we are performing tests on alpha and beta diversity results from each of these workflows to see if they correlate with expected outcomes from prior experiments. These tests will help us to determine the most strongly correlated workflows to the expected outcomes.
