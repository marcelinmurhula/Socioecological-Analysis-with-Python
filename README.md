# Socioecological Analysis in Kalonge, DRC

This repository contains the analysis and results from a Kaggle project focused on ecological impact and engagement levels.

## Project Overview

This project investigates the impact of various factors on consent to pay using a dataset of environmental and economic variables. Key factors analyzed include:

- Age
- Education Level
- Engagement Level
- Impact of Deforestation
- Primary Activity

## Objectives

1. **Age Impact on Engagement Levels and Willingness to Pay**
   - Assess whether age groups (20-40, 41-60, 61-80) significantly influence engagement levels and willingness to pay.

2. **Effect of Education Level on Consent to Pay**
   - Determine if education levels (Primaire, Secondaire, University) affect the consent to pay.

3. **Impact of Ecosystem Service Importance on Consent to Pay**
   - Examine how the perceived importance of ecosystem services influences consent to pay.

4. **Effect of Deforestation Impact on Consent to Pay**
   - Explore whether different impacts of deforestation affect consent to pay.

5. **Engagement Levels and Willingness to Pay**
   - Analyze how engagement levels affect willingness to pay.

## Methodology

- **Data Collection**: The dataset includes variables such as age, education level, engagement level, impact of deforestation, primary activity, and consent to pay.
- **Analytical Approach**: Statistical tests including ANOVA and multiple linear regression were used to evaluate the relationships between variables.

## Results

### Age Impact on Engagement Levels and Willingness to Pay

- **Engagement Levels**:
  - **F-statistic**: 1.575
  - **P-value**: 0.272
  - *Conclusion*: Age does not significantly affect engagement levels.

- **Willingness to Pay**:
  - **F-statistic**: 1.141
  - **P-value**: 0.374
  - *Conclusion*: Age does not significantly affect willingness to pay.

### Multiple Linear Regression Results

- **Model Fit**:
  - **R-squared**: 0.606
  - **Adjusted R-squared**: 0.290
  - **F-statistic**: 1.919 (p-value = 0.246)
  - *Conclusion*: The model explains a moderate amount of variability but is not statistically significant.

- **Coefficients**:
  | Predictor                    | Coefficient | P-value |
  |------------------------------|-------------|---------|
  | Age                          | 0.3463      | 0.826   |
  | Education Level              | 27.7538     | 0.111   |
  | Engagement Level             | -30.4441    | 0.197   |
  | Impact of Deforestation      | 7.4046      | 0.649   |
  | Primary Activity             | 5.9182      | 0.830   |

- **Diagnostics**:
  - Potential multicollinearity issues.
  - Residuals are approximately normally distributed.

### Visualizations

- **Partial Regression Plots**: Show the relationship between each predictor and consent to pay.
- **Heatmap of Correlations**: Illustrates correlations between variables.

## Discussion

- **Interpretation**: The model’s R-squared indicates a moderate fit, with no statistically significant predictors. Multicollinearity might affect the reliability of the coefficients.
- **Limitations**: Small sample size and multicollinearity issues suggest a need for a larger dataset and further refinement of the model.

## Conclusion

- **Summary**: The analysis shows a moderate model fit with no significant predictors. Further research and data collection are recommended to improve the robustness of the model.

## Usage

1. **Load the Dataset**: Modify the data loading section as needed.
2. **Run the Analysis Scripts**: Execute the provided scripts to reproduce the results.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

