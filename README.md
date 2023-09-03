# Prosper Loan Exploration
## by Damilola Esan


## Dataset

Prosper loan data contains information on loans facilitated by the peer-to-peer lending platform, Prosper. The dataset includes information on 113,937 loans with 81 variables including the loan amount, borrower's credit score, debt-to-income ratio, employment status, and loan status (e.g. current, charged off, defaulted)


## Summary of Findings

I focused on the Loan Status as my main feature of interest, the distribution of the values prompted me to re-categorize them into Active, Repaid, and Defaulted, with the majority of loans being Active. The exploration of other variables shows that the distribution of credit scores is right-skewed, indicating more individuals with lower credit scores. The borrower APR and borrower rate are roughly normally distributed, indicating variability in the rates offered by Prosper. However, the debt-to-income (DTI) ratio is right-skewed, with a wide range of borrower debt levels relative to income, but most borrowers have a relatively low DTI ratio. The distribution of the loan amount is multimodal, with borrowers typically seeking relatively modest amounts of loans. The majority of borrowers prefer a 36-month term, while the Prosper Rating and Income Range show that most borrowers have a C rating and earn between 25,000 and 74,999 dollars per year. 

The bivariate and multivariate analysis of the dataset focused on exploring the relationships between different variables, both categorical and numeric, and how they impact loan status. It shows that there are relatively low correlations between the numeric features. I decided to explore the relationships between categorical and numeric variables, as well as relationships between categorical variables using a combination of visualizations, such as boxplots, pointplot, and scatterplots. 

One key finding is that there is a significant relationship between borrower APR and loan status. The analysis shows that defaulted loans tend to have higher median APRs compared to repaid loans, suggesting that borrowers with higher APRs and rates may be more likely to default.

Another important relationship highlighted in the analysis is the relationship between borrower characteristics and DTI ratios. The analysis shows that a borrower's credit score is a significant determinant of their DTI ratio, and borrowers with lower credit scores are more likely to have higher DTI ratios. Additionally, the analysis shows that homeowner status, credit score, and income range are all important factors to consider when assessing the risk associated with a given loan application

## Key Insights for Presentation

For the explanatory presentation, I focused on the influence of the borrower's characteristics on the status of the loans present in the dataset. I started out by exploring the distribution of the loan status itself, then went ahead to plot the distribution of some numeric variables which include borrower's APR, borrower's rate and the debt-to-income (DTI) ratio.

I explored the relationship between variables by plotting the loan status against the borroower's APR and borrower's rate using a boxplot in a pair grid which proved to be insightful. Also plotted the loan status and income range on a clustered bar chart to see the loan performance of borrowers based on their income bracket.

Lastly, I plotted the loan amount and monthly loan payment on a scatter plot with a color encoding of the loan status to understand the influence of loan amount and monthly loan payment on repaid, active and defauulted loans.

For any questions or inquiries, please visit my **[website](https://www.bit.ly/damiesan)**.