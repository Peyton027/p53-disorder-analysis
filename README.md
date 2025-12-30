# p53 Intrinsic Disorder and Domain Analysis

## Overview
This project analyzes how intrinsic disorder and simple sequence features vary across functional domains of the human tumor suppressor protein p53. Using per-residue disorder predictions and hydrophobicity metrics, the analysis compares structured and intrinsically disordered regions to illustrate how biophysical properties align with protein function.

## Biological Question
How are intrinsic disorder and hydrophobicity distributed across the functional domains of p53, and how do these features distinguish regulatory regions from the structured DNA-binding core?

## Data
- Human p53 amino acid sequence (UniProt)
- Precomputed per-residue intrinsic disorder scores
- Literature-defined p53 domain boundaries

## Methods (Summary)
- Disorder scores were mapped to the p53 sequence by residue number.
- Functional domains were assigned using fixed residue ranges.
- Kyte–Doolittle hydrophobicity values were calculated and smoothed using a rolling window average.
- Domain-level comparisons were visualized using line plots and boxplots.
- All analyses were performed in R.

## Key Findings
- Regulatory regions of p53 (N-terminal transactivation domains and C-terminal tail) exhibit high intrinsic disorder and hydrophilicity.
- The DNA-binding domain shows low disorder and less negative hydrophobicity, consistent with a structured core.
- Hydrophobicity patterns closely mirror disorder distributions across domains.
- Linker regions display highly hydrophilic properties consistent with flexible boundary regions.

## Notes
This project is intended as a focused, descriptive analysis of a single protein and does not include experimental validation.
