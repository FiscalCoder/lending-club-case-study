# Lending Club Case Study: Loan Default Analysis

## Table of Contents
- [General Information](#general-information)
- [Steps to Perform EDA](#steps-to-perform-eda)
- [Key Findings and Conclusions](#key-findings-and-conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## General Information

Lending Club is a finance company that provides various types of loans, including personal loans, business loans, and medical expense loans, to urban residents. This case study aims to understand the driving factors behind loan defaults through exploratory data analysis (EDA).

**Key objectives:**
- Identify strong indicators of loan default
- Assist Lending Club in mitigating credit losses
- Improve portfolio and risk assessment strategies

By analyzing the provided dataset, we seek to pinpoint applicants at risk of defaulting on loans, enabling a reduction in credit losses while ensuring deserving applicants are not rejected.

## Steps to Perform EDA

1. **Load data and overview**
   - Import the dataset
   - Examine basic statistics and structure

2. **Data cleaning and standardization**
   - Handle missing values
   - Standardize data formats

3. **Univariate Analysis**
   - Analyze individual variables
   - Identify distributions and patterns

4. **Segmented Univariate Analysis**
   - Examine variables across different segments

5. **Bivariate Analysis**
   - Explore relationships between variables
   - Identify correlations and trends

6. **Conclusion**
   - Summarize key findings
   - Draw insights for decision-making

## Key Findings and Conclusions

Our analysis of the Lending Club dataset reveals several critical factors influencing loan defaults and overall portfolio performance:

#### Borrower Profile and Loan Characteristics
- The portfolio consists primarily of conservative, low-risk borrowers, with an 85% repayment rate.
- Most borrowers prefer moderate loan amounts and shorter 36-month terms.
- Debt consolidation and credit card refinancing are the most common loan purposes, indicating growing financial pressures.

#### Risk Factors for Loan Default
1. **Credit Quality:**
   - Lower credit grades (C-G) correlate with higher default rates.
   - Public bankruptcy records significantly increase default risk.

2. **Loan Terms:**
   - Longer loan terms (60 months) are associated with higher default rates.
   - Larger loan amounts and higher interest rates increase default probability.

3. **Financial Health Indicators:**
   - Higher debt-to-income (DTI) ratios correlate with increased defaults.
   - Lower annual incomes are associated with higher default risk.

4. **Loan Purpose:**
   - Small business loans show a higher tendency for default.

#### Risk Assessment and Lending Practices
- 42% of borrowers lack full income verification, presenting a potential risk.
- Counter-intuitively, unverified incomes receive lower interest rates, raising questions about risk assessment practices.
- Verification status alone is not a strong predictor of default rates.

#### Recommendations
1. Enhance risk assessment models to incorporate comprehensive borrower profiles, including DTI, bankruptcy history, and loan purpose.
2. Re-evaluate income verification processes and their impact on interest rate assignments.
3. Consider adjusting loan terms and amounts based on credit grade to mitigate default risk.
4. Implement targeted financial education initiatives to address growing demand for debt consolidation loans.
5. Explore opportunities for geographic market expansion while maintaining a balanced risk profile.

By implementing these insights, Lending Club can improve its portfolio performance, reduce default rates, and continue providing valuable financial services to borrowers while managing risk effectively.

## Technologies:
* Programming Language: Python
* Libraries: Pandas, Seaborn, Matplotlib, Numpy
* Tool: Google colab

## Acknowledgements

- [Pandas Official Site](https://pandas.pydata.org/)
- [Seaborn Official Site](https://seaborn.pydata.org/)
- [Matplotlib Official Site](https://matplotlib.org/)
- [NumPy Official Site](https://pypi.org/project/numpy/)

## Contact

Contributers:
- [@FiscalCoder](https://github.com/fiscalcoder)
- Ishan Bhowmik



