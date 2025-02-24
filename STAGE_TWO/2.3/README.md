# Task 2.3:  Botany and Plant Science

## Description
This task involves analyzing metabolic responses of engineered mutant crops compared to wild-type (WT) plants under pesticide treatment. Scientists took metabolic readings at 8 and 24 hours to assess how the engineered mutants respond compared to WT plants. The dataset provides information about the metabolic changes observed in response to the pesticide treatment.

## Dataset Information
- **Dataset Link**: [Pesticide Treatment Data](https://raw.githubusercontent.com/HackBio-Internship/2025_project_collection/refs/heads/main/Python/Dataset/Pesticide_treatment_data.txt](https://raw.githubusercontent.com/HackBio-Internship/2025_project_collection/refs/heads/main/Python/Dataset/Pesticide_treatment_data.txt))
- The dataset includes metabolic response values for WT and mutant plants under different treatment conditions over time.

## Objectives
1. **Calculate the metabolic response difference (ΔM)**:
   - Compute the difference between the DMSO treatment and the 24-hour treatment for both WT and mutant plants.

2. **Generate a Scatter Plot**:
   - Plot ΔM for WT and mutants.
   - Fit a line with a y-intercept of 0 and a slope of 1.

3. **Calculate Residuals and Classify Metabolites**:
   - Compute the residual for each point based on the fitted line.
   - Apply a chosen residual cutoff value.
   - Color metabolites based on residual values:
     - **Grey**: Residuals within the cutoff range.
     - **Salmon**: Residuals outside the cutoff range.

4. **Identify Outlier Metabolites**:
   - List metabolites that fall outside the residual threshold.
   - Analyze trends in metabolic responses.

5. **Generate Line Plots for Selected Metabolites**:
   - Pick any 6 outlier metabolites.
   - Plot their metabolic response from 0h, 8h, and 24h.
   - Interpret trends in metabolic response over time.

## Expected Outcomes
- **Scatter plot** of ΔM for WT and mutant plants with fitted regression line.
- **Colored classification of metabolites** based on residuals.
- **Identification of key metabolites** exhibiting significant deviations.
- **Line plots of selected metabolites** to visualize metabolic response trends over time.
- **Biological interpretation** of the observed trends.

## Explanation of Results
- The scatter plot helps visualize metabolic differences between WT and mutants.
- The residual analysis highlights metabolites with significant metabolic shifts.
- The line plots provide insights into how specific metabolites evolve over time under treatment.
- Biological interpretation can reveal the impact of genetic modifications on pesticide resistance.


---
**Note**: Detailed observations and conclusions are embedded as comments in the final code implementation.

