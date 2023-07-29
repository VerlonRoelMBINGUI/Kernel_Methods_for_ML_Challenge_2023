# AMMI_Kernel_Methods_for_ML_Challenge_2023
In this project, we propose many kernels methods from scratch for DNA Sequence classification.
Team name: Bourbaki's KM_Team

This project was done in collaboration with [Dieu-Donne Fangnon](https://github.com/dfangnon)

The  [link]( https://www.kaggle.com/competitions/kernel-methods-ammi-2023)  brings you to the hackathon website

The goal of the data challenge is to learn how to implement machine learning algorithms, gain understanding about them and adapt them to structural data.
For this reason, we have chosen a sequence classification task: predicting whether a DNA sequence region is binding site to a specific transcription factor.

Transcription factors (TFs) are regulatory proteins that bind specific sequence motifs in the genome to activate or repress transcription of target genes.
Genome-wide protein-DNA binding maps can be profiled using some experimental techniques and thus all genomics can be classified into two classes for a TF of interest: bound or unbound.
In this challenge, we will work with three datasets corresponding to three different TFs.

We design 4 kernels models:

* SVM with Sum of many Mismatch Kernels 
* SVM with  Mismatch Kernels
* SVM with  Spectrum Kernels
* SVM with Gaussian Kernel

We obtained a private score of0.67600 on the leaderboard and ranked 2nd at the end of the competition.
