# Loan Approval Analysis for Young and Mid-Career Adults

## Abstract

This project investigates how employment length, income, loan amount, and education level affect loan approval rates for young adults (ages 18-28) compared to mid-career adults (ages 28-38). With a focus on education levels (high school diploma, bachelor’s degree, master’s/PhD), we aim to uncover trends that provide actionable insights for young borrowers and improve financial literacy. Using statistical tests and data visualizations, we explored the significance of various factors influencing loan approvals and repayment behavior.

## Reasearch Question

* How do employment length, income, and loan amount affect loan approval rates for young adults with varying educational levels?
* How do these effects compare to mid-career adults with similar education?

## Hypothesis

Young adults with higher education levels (master’s/PhD) would have higher home mortgage approval rates. However, mid-career adults (28+) were predicted to have higher overall approval rates due to job stability and experience.

## Dataset

- Name: Loan Default Prediction Dataset
- Source: Kaggle Dataset
- Observations: 255,347
- Variables: 18
- Link: https://www.kaggle.com/datasets/nikhil1e9/loan-default

Key variables analyzed include:
  - Age (proxy for life stage/income potential)
  - Income (financial stability)
  - LoanAmount (affordability/risk)
  - MonthsEmployed (job stability)
  - Education (employability/earning potential)
  - EmploymentType (income predictability)
  - LoanPurpose (risk)
  - Default (loan repayment binary)

## Methodology

### Data Cleaning
- Removed unnecessary columns.
- Identified and resolved outliers and missing values.
- Standardized units and corrected typos in categorical variables.

### Analysis Techniques:
- Generated scatter plots for relationships (e.g., Age vs. Income, LoanAmount).
- Conducted T-tests to determine statistical significance between groups.
- Bar plots visualized loan purposes by age group.

## Results

- No significant differences in loan amounts based on education level.
- Mid-career adults are more likely to repay loans than young adults, likely due to greater financial stability.
- Income, months employed, and loan purpose were significant predictors of loan approval.

## Conclusion

Our research highlights important trends in loan approvals for young and mid-career adults, providing actionable insights for borrowers, lenders, and policymakers.

- Young Adults vs. Mid-Career Adults:
  - Mid-career adults consistently demonstrate higher loan approval and repayment rates, likely due to greater financial stability, longer employment histories, and more predictable income streams. These findings suggest that young adults, despite their education levels, may face additional challenges in securing loans or favorable terms due to perceived financial risks.

- Education and Financial Stability:
  - Contrary to our hypothesis, educational attainment did not significantly impact loan approval rates within the young adult demographic. This result underscores the importance of other factors, such as income and employment stability, over formal education in influencing lender decisions.

- Actionable Insights:
  - Young adults seeking loans should focus on building a stable income and employment history to increase approval odds. Financial institutions may consider revisiting approval criteria to support younger borrowers without penalizing them for shorter employment histories.

- Future Work:
  - Incorporating additional variables, such as credit scores and debt-to-income ratios, could enhance the analysis.
  - Expanding the dataset to include geographic data could provide insights into regional disparities in loan approvals.
  - Exploring machine learning models for predictive analysis could complement statistical approaches and offer more granular insights into loan approval trends.

By understanding these dynamics, young borrowers can make informed financial decisions, and lenders can refine their criteria to better serve diverse demographics. Future research should delve deeper into the intersection of age, financial stability, and creditworthiness to promote equitable lending practices.











