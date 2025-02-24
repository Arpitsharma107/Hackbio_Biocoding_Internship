# Task Code 2.4: Biochemistry & Oncology

## Overview
Protein structures are strongly connected to their functions. However, at the amino acid level, not all amino acids contribute equally to structure and function. Galardini and colleagues investigated the impact of all possible individual, non-synonymous nonsense mutations on protein structure and function.

- **Functional Impact**: Computed using SIFT scores.
- **Structural Impact**: Computed using FoldX scores (in kCal/mol).

This task involves analyzing the relationship between SIFT scores and FoldX scores to determine how different mutations impact protein function and stability.

## Dataset Links
- **SIFT Dataset**: [Download here](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/sift.tsv](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/sift.tsv))
- **FoldX Dataset**: [Download here](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/foldX.tsv](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/foldX.tsv))

## Task Requirements
1. **Data Processing**: Load and clean the SIFT and FoldX datasets.
2. **Merge Data**: Combine both datasets based on common identifiers (e.g., mutation ID).
3. **Analysis**:
   - Determine the correlation between SIFT scores and FoldX scores.
   - Generate a scatter plot of SIFT scores vs. FoldX scores.
   - Identify mutations with high structural impact but low functional impact and vice versa.
4. **Statistical Testing**:
   - Perform statistical analysis to determine if there is a significant relationship between functional and structural impact.
5. **Visualization**:
   - Generate heatmaps or box plots to represent the distribution of SIFT and FoldX scores.
   
## Expected Outcomes
- A well-documented script that processes and analyzes the datasets.
- Clear visualizations illustrating the correlation between functional and structural impact.
- Insights into which mutations significantly impact protein stability or function.

## Explanation
- Mutations with **low SIFT scores** indicate a high probability of functional impact.
- Mutations with **high FoldX scores** suggest a strong destabilizing effect on protein structure.
- A strong correlation between these scores may indicate that structural destabilization is a key driver of functional loss.

For further details, refer to the original datasets and their associated documentation.

