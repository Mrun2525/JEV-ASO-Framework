# Computational Workflow

## Overview

This directory documents the complete computational workflow used in the manuscript:

**An Integrated Bioinformatics Framework for Host Selenoprotein-Guided Prioritization of Antisense Oligonucleotide Targets in Japanese Encephalitis Virus**

The framework was designed to identify and prioritize antisense oligonucleotide (ASO) target sites across the Japanese Encephalitis Virus (JEV) genome using a deterministic multi-parameter computational strategy.

Unlike conventional ASO screening pipelines that rely primarily on thermodynamic prediction, this workflow integrates multiple independent computational evidence layers including:

- genome-wide hotspot identification
- RNA-RNA interaction thermodynamics
- RNA structural accessibility
- transcriptome-wide host selectivity
- evolutionary conservation
- synonymous-site conservation
- mutational robustness
- sequence developability
- host selenoprotein interaction profiling

Each stage narrows the candidate space until a final prioritized ASO candidate is obtained.

---

## Workflow Summary

Step 1
Genome-wide hotspot discovery

↓

Step 2
Generation of overlapping ASO candidates

↓

Step 3
Thermodynamic interaction prediction (IntaRNA)

↓

Step 4
RNA accessibility analysis (RNAplfold)

↓

Step 5
Host transcriptome off-target analysis

↓

Step 6
Evolutionary conservation

↓

Step 7
Consensus RNA secondary structure

↓

Step 8
Synonymous-site conservation (SynPlot2)

↓

Step 9
Mutational robustness simulation

↓

Step 10
Developability assessment

↓

Step 11
Host selenoprotein interaction analysis

↓

Step 12
Integrated candidate prioritization

---

## Reproducibility

The scripts included in this repository reproduce the analyses described in the manuscript.

Software versions, command-line parameters, and datasets correspond to those reported in the Materials and Methods section.

No experimental data are required to reproduce the computational analyses.
