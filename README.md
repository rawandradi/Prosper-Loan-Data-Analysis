# Prosper Loan Data Analysis

## Introduction
This project analyzes the **Prosper Loan Dataset**, which contains detailed loan and borrower information from the Prosper peer-to-peer lending platform. The original dataset includes 113,937 loan records with 81 variables covering loan terms, interest rates, borrower credit information, income, and loan status.

After data cleaning to remove missing or incomplete records, the cleaned dataset contains 77,557 entries and 13 key variables related to loan and borrower details.

## Objective
The primary goal is to explore factors that influence the **Borrower APR** (annual percentage rate), which reflects the cost and risk of loans on the platform. Secondary focuses include understanding loan status outcomes and evaluating how credit ratings affect loan terms.

## Dataset Features
Key features used in this analysis:

- **BorrowerAPR:** Annual percentage rate assigned to a borrower  
- **ProsperRating (Alpha):** Credit rating assigned by Prosper  
- **ProsperScore:** Numeric borrower risk score  
- **IncomeRange & StatedMonthlyIncome:** Financial capacity indicators  
- **EmploymentStatus:** Employment stability  
- **DebtToIncomeRatio:** Borrower's debt burden  
- **CreditScoreRangeLower & CreditScoreRangeUpper:** Creditworthiness range  
- **LoanOriginalAmount & Term:** Loan characteristics  
- **IsBorrowerHomeowner:** Financial reliability indicator  

## Methodology
- Imported and cleaned data by removing rows with missing values in key columns.  
- Conducted exploratory data analysis (EDA) including univariate, bivariate, and multivariate explorations.  
- Visualized relationships between borrower features and BorrowerAPR using Python libraries Pandas, Matplotlib, and Seaborn.  

## Key Findings and Conclusions

- Creditworthiness, as measured by **Prosper Rating** and **Prosper Score**, is the strongest predictor of **Borrower APR**; higher credit ratings correlate with lower interest rates.  
- Income influences APR but to a lesser extent; borrowers with similar incomes can have different APRs based on their credit scores.  
- Higher **Debt-to-Income Ratios** slightly increase APRs, reflecting greater perceived risk.  
- Longer loan terms (e.g., 60 months) are associated with higher risk and a greater proportion of loans charged off or defaulted.  
- Combining multiple borrower features provides better insight into APR variation than analyzing single factors alone.  
- Rigorous data cleaning and outlier removal improved the accuracy and reliability of the analysis.

## Tools and Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

## Usage
- Review the accompanying Jupyter Notebook (`prosper_loan_analysis.ipynb`) for detailed steps, code, and visualizations.  
- Use the cleaned dataset for further modeling or research.  
- Leverage insights from this analysis to understand borrower risk profiles and loan pricing on peer-to-peer lending platforms.

## License
This project is for educational and research purposes.
