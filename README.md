# Payne Lab: Swin Transformer and Automated Data Labeling

I’m currently leading efforts to develop AI for semantic segmentation of carbonate thin sections in Prof. Jonathan Payne’s lab at Stanford, supporting paleobiology and mass-extinction research. We are deploying four models across labeled and unlabeled high-resolution petrographic datasets from the Cretaceous and the Permian–Triassic, with two manuscripts in preparation. My primary contributions include building the end-to-end modeling pipeline, designing automated methods to improve training labels, and co-drafting the manuscripts.

This repository contains a representative sample of my work in the Payne Paleobiology Lab, organized around two core components:

1) Model training pipeline
The training pipeline for one of the four models, featuring a novel use of a Swin Transformer backbone as a framework for hierarchical feature learning.
   
2) Automated labeling and mask refinement
Due to the dense, information-rich nature of the images, as well as scarcity of labels, a large part of my work focuses on automated training-data labeling. This section includes scripts for an automated labeling scheme I designed to improve the quality of our limited ground-truth annotations, along with relabeling utilities and side-by-side visualizations of the original versus refined masks.
