# Computational Workflow Scripts

## Overview

This directory contains all Python and shell scripts used in the computational framework described in the manuscript:

**An Integrated Bioinformatics Framework for Host Selenoprotein-Guided Prioritization of Antisense Oligonucleotide Targets in Japanese Encephalitis Virus**

The workflow was designed to identify and prioritize antisense oligonucleotide (ASO) target sites within the Japanese Encephalitis Virus (JEV) genome by integrating multiple computational evidence layers, including thermodynamic interaction strength, RNA structural accessibility, evolutionary conservation, host selectivity, mutational robustness, and developability.

Each script represents a defined stage of the computational pipeline and should be executed sequentially unless otherwise indicated.

## Workflow Organization

| Step | Script | Purpose |
|------|---------|---------|
| STEP1 | Genome scanning | Identification of candidate viral regions |
| STEP2 | ASO design | Generation of candidate ASOs |
| STEP3 | Accessibility | RNA structural accessibility analysis |
| STEP4 | DeltaG | Thermodynamic interaction analysis |
| STEP5 | Off-target | Human transcript off-target screening |
| STEP6 | Conservation | Evolutionary conservation analysis |
| STEP7 | Selenoprotein | Host selenoprotein interaction analysis |
| STEP8 | Developability | Candidate prioritization |
| STEP9 | Chemistry | Chemical feasibility assessment |
| STEP10 | Delivery | Delivery-related evaluation |
| STEP11 | Host specificity | Host selectivity assessment |

## Software Requirements

The workflow was developed using Python 3.x together with established bioinformatics software including BLAST+, IntaRNA, MAFFT, ViennaRNA, RNAplfold and associated Python utilities.

Detailed software versions are provided in the repository root.

## Notes

These scripts are provided to ensure complete computational reproducibility of the published workflow.

The scripts reproduce the computational analyses presented in the manuscript and do not constitute experimentally validated therapeutic predictions.
