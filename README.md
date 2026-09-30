# Week-4-Hypothesis-Testing
Hypothesis testing on the UCI Bank Marketing dataset using Python and statistical analysis.

## Project Overview

This project focuses on hypothesis testing using the UCI Bank Marketing dataset. The objective is to determine whether there is a statistically significant difference in the average account balance between customers who subscribed to a term deposit and customers who did not.

## Dataset

The analysis uses the `bank-full.csv` dataset containing 45,211 customer records and 17 variables.

The target variable is:

- `y` – whether the customer subscribed to a term deposit (`yes`/`no`)

The main numerical variable used for hypothesis testing is:

- `balance` – customer's account balance

## Research Question

Is there a significant difference in the average account balance between customers who subscribed to a term deposit and those who did not?

## Hypotheses

### Null Hypothesis (H₀)

There is no significant difference in the average account balance between subscribed and non-subscribed customers.

### Alternative Hypothesis (H₁)

There is a significant difference in the average account balance between subscribed and non-subscribed customers.

## Statistical Test

An independent two-sample Welch's t-test was used to compare the average account balances of the two groups.

The significance level was set at:

α = 0.05

## Analysis Performed

- Loaded and explored the dataset
- Examined the target variable
- Separated customers into subscribed and non-subscribed groups
- Calculated descriptive statistics
- Compared average account balances
- Created visualizations
- Performed an independent two-sample Welch's t-test
- Interpreted the p-value
- Made a statistical conclusion

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Files

- `Week_4_Hypothesis_Testing.ipynb` – Python analysis and hypothesis testing
- `Week_4_Hypothesis_Testing_Report.docx` – Detailed project report

## Conclusion

The hypothesis test evaluates whether the observed difference in average account balance between the two customer groups is statistically significant. The final conclusion is based on the calculated p-value and the significance level of 0.05.
