# The Dynamics of Inducible Genetic Circuits

This repository contains supporting code for:

- Yang Z*, Rousseau RJ*, Mahdavi SD*, Garcia HG, Phillips R. The dynamics of inducible genetic circuits. *In preparation* (2025)
The contents of the repository were used to generate the results found in figures throughout this paper. This work evaluates the dynamics of self-activation, mutual repression, and feed-forward loop in gene regulation as a function of allosteric effector concentration, and explores parameter sensitivity in each of these model systems.

## Layout
---
The repository is organized into three directories, each corresponding to a different regulatory model/section within the paper: 

## `autoactivation`
This directory contains all Jupyter notebooks used to model bistable dynamics in auto-activation, with notebooks:

1. Dynamics of auto-activation (Figs. 8-10)
2. Regimes of bistability (Figs. 11, 12)
3. Timescale for stabilization (Figs. 13)
4. SI: Appendix Figs. 28-31

## `mutualrepression`
This directory contains all Jupyter notebooks used to model bistable dynamics in mutual repression, with notebooks:

1. Dynamics of mutual repression (Figs. 15-16)
2. Regimes of bistability (Figs. 17-18, SI Fig. 32)
3. Timescale for stabilization (Fig. 19)

## `feedforward`
This directory contains all Jupyter notebooks used to model input signal response in coherent and incoherent feed-forward loops, with notebook:

1. Feed forward (Figs. 21, 22, 24, 25)
2. SI: Appendix Figs. 34-36

Each .ipynb notebook outputs .pdf files for results that were used to generate the final figures seen in the paper. 

------------------------------------------
*: These authors contributed equally to this work.
