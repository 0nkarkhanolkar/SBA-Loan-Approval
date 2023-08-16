# Small-Businesss-Loan-Default

One day, while surfing on my phone, I saw a video of the movie "The Big Short." It brought my attention to the 2008 Global Financial Crisis.
So I decided to look into lending practices used to give out loans and the main factors behind determining which loan is high risk.
I learned about the Small Business Administration and its vast history of funding various entrepreneurial ventures during my research.

For my readers, assume you are a loan officer at a bank and are asked to approve or deny a loan by assessing its risk of default.
The business objective, and your task, is to help the hierarchy understand the factors that increase the risk of repayment default.
Our analysis will make the loan approval process easier & reduce the bank's probability of an unprofitable transaction.

For our analysis, we have assumed that all loans over a term of 20 years have been lent for Real Estate, but keep in mind that does not necessarily have to be true. I have also examined the effect of the Great Recession between 2007-09 on the default rate of Small Businesses.

My approach is divided into the following sections:
1.	Data cleaning - drop unnecessary columns, fill in missing values
2. 	Feature engineering - build new features for a deeper understanding
3.	Outlier detection & removal - identify extreme outliers and remove them
4.	Exploratory data analysis - look at the cleaned data & distribution of the approved amount
5.	Data visualization - display visually appealing plots and histograms
6.	Model building - construct multiple models (logistic regression, decision trees, xgboost)

In the end, I concluded that -

1. Only 0.011% of loans that defaulted were backed by Real Estate. On the contrary, loans not backed by Real Estate defaulted by 0.234% i.e. about 21 times more than the ones backed by Real Estate. Even though the default rate for loans not backed by real estate is pretty small (0.234%), it can be said that the chances of default for a loan not backed by Real Estate are at least 20 times more than for a loan backed by Real Estate.

2. Only 0.21% of the loans that defaulted were active during the Great Recession period of 2007-09. On the other hand, 0.23% of the loans defaulted during the other years. Hence, the Great Recession has not affected the default rates of Small Businesses as much.
   

Here are some of the visualizations:

![image](https://github.com/0nkarkhanolkar/SBA-Loan-Approval/assets/98197574/4b6b7c20-f3d8-4ba7-b739-cc81059cdbb0)

![image](https://github.com/0nkarkhanolkar/SBA-Loan-Approval/assets/98197574/8d42891f-4d37-4709-a553-b40851e2e018)
