---
layout: bio
datatype: bio

title: Arron Shiffer
picture: "arron-shiffer/profile.png"
abstract: "I am a new PhD student in Dr. Caporaso's lab. I am currently working on some benchmarking studies looking at four different multiple sequence aligners with "Lane mask" filtering vs strictly entropy based positional alignment filtering."
---


# Background
My background is primarily in Physics. I have an M.S. in Physics from University of California, Riverside
and a B.S. in Physics from Northern Arizona University. In addition, I have a B.S in Astronomy and a B.A. in
Philosophy from NAU.

# Interests

I am currently working on benchmarking studies looking at four different multiple sequence aligners (MUSCLE, MAFFT, PyNAST, and SSU-ALIGN). Each of these is being coupled with either Lane mask or strictly entropy based positional alignment filtering using SciKit-Bio. We are looking to find out if the phylogenetic trees and diversity results are as good or better than the use of PyNAST multiple
sequence alignment with Lane mask positional alignment filtering. We are creating trees using FastTree, creating distance matrices using Scikit-Bio, and then performing Mantel tests on those trees using Scikit-Bio to get a correlation coefficient. Additionally, we applied a Robinson-Foulds distance metric to test similarity of the trees created by each method.
