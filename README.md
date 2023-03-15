# nist_experiments


Experiments to analyse the K-factor distribution from NIST radio survey channels.

The goals of the experiments are:

* evaluating the perceived (application-level) quality of radio channels characterised by different K-factors
* comparing three K-factor estimators in terms of their perceived channel quality
* compare the quality of a measurement-based channel and that of a flat-fading Rician channel, where the estimated K-factor of the measurements-based channel is the same as that of the flat-fading Rician channel.

This repository contains:

* sionna_kfactor_analysis.ipynb -- Jupyter notebook performing the above analysis
* pickle and csv files containing channel measurements (CIRs) and estimated K-factor distributions
* nist_cir_processing.ipynb -- Jupyter notebook for processing CIRs from NIST datasets.
