# Automobile Insurance Claim Fraud Factors
# Exploratory Data Analysis / Hypothesis Testing
# Summary/Overview 
This project used exploratory data analysis and statistical techniques in Python to prove or disprove a hypothesis based on automobile claims fraud variables.
# Hypotheses
There is no difference in the means of variables in the fraud reported subset and the same variables in the fraud not reported subset.  
There is no significant linear relationship between the fraud reported target variable and any of the claim transaction variables.
# Data
Fraudulent Insurance Claims dataset located at https://www.kaggle.com/patilk1/fraudulentinsuranceclaim
# Techniques
•	Histograms
•	Descriptive statistics
•	Probability mass function
•	Cumulative distribution function
•	Probability plot
•	Scatter plots
•	Point-Serial Correlation
•	Permutation tests
# Outcome
Through statistical analysis and hypothesis testing, I rejected the null hypothesis that there is no difference in the means of Total Claim Amount variable in the fraud reported subset versus the fraud not reported subset, but concluded that it is plausible that the observed difference in means between the other variables in the fraud reported subset and the fraud not reported subset are just the result of random sampling and rejected the null hypothesis for all variables other than the Total Claim Amount variable.
Regarding the hypothesis that there is no significant linear relationship between the fraud reported target variable and any one of the claim transaction variables, the correlation hypotheses testing showed that the null hypothesis should be accepted as none of the p-values of the claim transactions variables were statistically significant. 
# Resources
This analysis utilizes supported code from Allen Downey's ThinkStats2 https://github.com/AllenDowney/ThinkStats2

