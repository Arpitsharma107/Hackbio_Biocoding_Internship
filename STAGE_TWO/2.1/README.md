# Microbial Growth Curve Analysis

## Task Code 2.1: Microbiology

This project is part of the HackBio Internship Stage 2. The objective is to analyze microbial growth curves and assess the impact of gene knock-out (-) and knock-in (+) strains on growth dynamics.

### Dataset
- **Dataset URL:** [mcgc.tsv](https://raw.githubusercontent.com/HackBio-Internship/2025_project_collection/refs/heads/main/Python/Dataset/mcgc.tsv](https://raw.githubusercontent.com/HackBio-Internship/2025_project_collection/refs/heads/main/Python/Dataset/mcgc.tsv))
- **Metadata URL:** [mcgc_METADATA.txt](https://github.com/HackBio-Internship/2025_project_collection/blob/main/Python/Dataset/mcgc_METADATA.txt](https://github.com/HackBio-Internship/2025_project_collection/blob/main/Python/Dataset/mcgc_METADATA.txt))

### Objectives
1. **Plot Growth Curves:**
   - For each strain, generate a growth curve of OD600 vs. Time.
   - Overlay the knock-out (-) and knock-in (+) strains on the same plot.

2. **Determine Carrying Capacity Time:**
   - Using the function from the previous stage, calculate the time taken to reach carrying capacity for each strain/mutant.

3. **Scatter Plot:**
   - Generate a scatter plot comparing the time to reach carrying capacity for knock-out (-) and knock-in (+) strains.

4. **Box Plot:**
   - Generate a box plot illustrating the distribution of time taken to reach carrying capacity for both knock-out (-) and knock-in (+) strains.

5. **Statistical Analysis:**
   - Assess whether there is a significant statistical difference between the time taken for knock-out strains to reach carrying capacity compared to knock-in strains.

6. **Observations & Interpretation:**
   - Provide a summary of findings in the form of comments in the code.

### Requirements
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- SciPy
- NumPy

### Usage
1. Clone the repository or download the script.
2. Ensure all dependencies are installed using:
   ```bash
   pip install pandas matplotlib seaborn scipy numpy
   ```
3. Run the script:
   ```bash
   python growth_curve_analysis.py
   ```
4. The output will include:
   - Growth curves for each strain with knock-out and knock-in overlaid.
   - Scatter plot of time to carrying capacity.
   - Box plot of carrying capacity time comparison.
   - Statistical analysis results.

### Output
- **Growth Curves**: OD600 vs. Time for each strain.
- **Scatter Plot**: Comparison of time to carrying capacity for knock-out and knock-in strains.
- **Box Plot**: Distribution of carrying capacity time for knock-out and knock-in strains.
- **Statistical Analysis**: Summary of differences between knock-out and knock-in strains.

### Explanation of Findings
- The results will indicate how gene modifications affect microbial growth dynamics.
- Statistical significance tests will reveal whether knock-out strains differ significantly from knock-in strains in their growth rates.
- Observations and explanations are included in the code as comments.

---

This project is part of the **HackBio Internship Stage 2 Task 2.1** focusing on **Microbiology Growth Curve Analysis**.

