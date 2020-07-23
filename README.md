# BCF-discussion-paper
This repository contains R scripts to run the simulation results and to generate the plots of the discussion paper Bayesian Regression Tree Models for Causal Inference: Regularization, Confounding, and Heterogeneous Effects (Hanh et al, 2020).

Basically, the files with prefix "Run_" run some algorithms on synthetic data generated according to the Section 6.1 of Hahn et al (2020). Below, we present a brief explanation about the scripts
 
1 - Run_BCF: it runs Bayesian Causal Forest (Hahn et al, 2020); \\
2 - Run_BART_BMA: it runs BART-BMA (Hernández et al, 2018); \\
3 - Run_BART_DART_CRF: it runs BART (Chipman et al, 2010), DART (Linero, 2018) and Causal Random Forests (Athey, arxiv 2018); \\
4 - Run_BCF_BMA: it runs the Bayesian Causal Forest with Bayesian Model Averaging. This can be viewed as the BCF approach to BART-BMA; \\
5 - Run_MOTR_BART: it runs BART with Model Trees (Prado et al, arxiv 2020).

