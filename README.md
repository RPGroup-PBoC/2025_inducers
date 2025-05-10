# The Dynamics of Inducible Genetic Circuits

This repository contains supporting code for:

- Yang Z*, Rousseau RJ*, Mahdavi SD*, Garcia HG, Phillips R. The Dynamics of Inducible Genetic Circuits. *In preparation* (2025)

The contents of the repository were used to generate the results found in figures throughout this paper. This work evaluates the dynamics of self-activation, mutual repression, and feed-forward loop in gene regulation as a function of allosteric effector concentration, and explores parameter sensitivity in each of these model systems.

## Layout
---
The repository is organized into four directories, each corresponding to a different regulatory model/section within the paper:

## `effectors`
This directory contains the Jupyter notebook used to discuss the role of effectors and generate Figures 5 and 6 of the paper. 

## `autoactivation`
This directory contains all Jupyter notebooks used to model bistable dynamics in auto-activation, with notebooks:

1. Dynamics of auto-activation (Figs. 8-10)
2. Regimes of bistability in auto-activation (Fig. 11, Appendix Fig. 28)
3. Comparison of Hill function and thermodynamic models (Fig. 12, Appendix Figs. 30-31)
4. Timescale for relaxation to steady state in auto-activation (Fig. 13, Appendix Fig. 33)
5. SI: Maximal and minimal cooperativity for observing bistability in auto-activation (Appendix Figs. 29, 32)

## `mutualrepression`
This directory contains all Jupyter notebooks used to model bistable dynamics in mutual repression, with notebooks:

1. Dynamics of mutual repression (Figs. 15-16)
2. Phase diagram for mutual repression (Fig. 17, Appendix Fig. 34)
3. Bistability in mutual repression as a function of cooperativities and expression rate (Fig. 18)
4. Timescale for relaxation to steady state in mutual repression (Fig. 19)

For viewer convenience, this directory also contains several .csv files with the output bifurcation threshold values that generate the higher-resolution version of Fig. 18(B) found in the paper. Note that while these files are included for convenience given the longer run time required by the step size in phase space, one can also generate these same outputs by appropriate modification of the variable ```nsampling```, as commented in the code.

## `feedforward`
This directory contains all Jupyter notebooks used to model input signal response in coherent and incoherent feed-forward loops, with notebook:

1. Dynamics of the feed-forward loop (Figs. 21, 22, 24, 25, Appendix Figs. 35 - 37)

------------------------------------------
*: These authors contributed equally to this work.
