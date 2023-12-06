# Lending Club Case Study

Managing its loan approval process presents a significant challenge for Lending Club, a consumer finance marketplace that specializes in providing a range of loans to urban customers. The corporation has to make wise selections when assessing loan applications in order to reduce losses, mostly from loans given to applicants who are deemed "risky."

When borrowers default on their loans or fail to repay them, they suffer these monetary losses, also known as credit losses. Put more simply, the borrowers who have been classified as "charged-off" are the ones who have caused the company's most losses.

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives

The goal is to identify loan applicants who are most likely to default so that credit losses can be minimized. By employing the supplied [dataset](./loan.csv) for exploratory data analysis (EDA), this case study seeks to accomplish this objective.

The goal of the organization is to identify the characteristics that are strong predictors of loan default, or the driving causes, or driver variables, behind loan default. This information can be used by the business for risk assessment and portfolio management.

The primary objective of this exercise is to assist Lending Club in mitigating credit losses. This challenge arises from two potential scenarios:

1. Identifying applicants likely to repay their loans is crucial, as they can generate profits for the company through interest payments. Rejecting such applicants would result in a loss of potential business.
2. On the other hand, approving loans for applicants not likely to repay and at risk of default can lead to substantial financial losses for the company.

## Conclusions

1. **Risk Assessment for Grades B, C, etc**: Given that the majority of "Charged Off" loans are the result of loan applicants from Grades B, C, and D, the corporation ought to think about enforcing more stringent risk assessment and underwriting standards for applicants belonging to these grades.

2. **Subgrades**: Candidates with Subgrades B3, B4, and B5 should receive particular attention because they have a higher likelihood of charging off. You can think about lowering the loan amounts or putting in place more risk mitigation measures.

3. **Term**: The corporation ought to think about assessing the risk involved with longer-term loans and possibly restricting the maximum term or modifying interest rates in accordance with the likelihood of default that applicants who choose 60-month loans have.

4. **Experience**: The likelihood of default is higher for loan applicants who have 10 or more years of experience. This implies that creditworthiness may not always be determined by experience alone. The business ought to employ a more thorough credit scoring system that takes into account additional risk-related variables.

5. **Positive Growth Trend**: The market is growing, as seen by the consistent rise in loan applications between 2007 and 2011. By having a competitive advantage in the market and upholding risk management, the business can profit from this trend.

6. **Seasonal Trends**: Probably as a result of the holidays, December and Q4 see a spike in loan applications. In order to satisfy client demands, the business should plan for higher demand at certain times and make sure processing is done quickly.

7. **Debt Consolidation Risk**: The company should carefully assess applicants seeking debt consolidation loans and may need to modify interest rates or provide financial counseling services, as debt consolidation is the category with the highest number of loans and high default rates.

8. **Housing Status**: Those with mortgages or rents have a higher default rate. When evaluating a borrower's ability to repay a loan, the underwriting procedure may take this information into account.

9. **Verification Process**: Loan applicants who have been vetted are more likely to default than those who have not. The business should examine its verification procedure to make sure it evaluates applicants' creditworthiness accurately and take any necessary modifications into consideration.

10. **Geographic Risk**: There is a higher likelihood of default for loan applicants hailing from states such as California (CA), Florida (FL), and New York (NY). The business should keep an eye on regional risk patterns and modify lending policies or interest rates in these locations as necessary.

11. **High Loan Amounts**: There is a larger likelihood of default for applicants who receive loans of $15,000 or more. By carrying out more in-depth evaluations for larger loan requests and possibly limiting loan amounts for applicants that pose a greater risk, the organization can reduce this risk.

12. **Interest Rates**: Default rates in the range of 13%–17% and high DTI ratios are linked. Reviewing its procedure for determining interest rates and possibly modifying them in light of DTI ratios will help the company better match rates to the borrower's capacity to repay.

13. **Annual Income**: There is a greater chance of default for applicants whose yearly income is less than $40,000. To guarantee affordability for borrowers, the business might think about providing tools for financial education or establishing limit loan amounts based on income levels.

## Technologies Used

- [Python](https://www.python.org/) - version 3.11.4
- [Matplotlib](https://matplotlib.org/) - version 3.7.1
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 1.5.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2

