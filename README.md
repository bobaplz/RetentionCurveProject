# RetentionCurveProject
#Healthcare #RetentionCurve #Python # Exploratory Data Analysis #Descriptive Statistics #Regression model # Inferential Statistics#Pandas #Matplotlib #Seaborn #Statsmodels #Jupyternoteboo

-------------------------------------

## General Outlook / Objectives

This project has been constructed with a Coholt Analysis for the case when a healthcare company (e.g. ) to analyze retention rate of the customers at the coholt level. 

**Part 1** 

Customer Life Time Value (LTV) is measured for each cohort, which consists of all members starting in a given calendar month. There are several metrics that impact LTV:  

-	Monthly Retention Rates across the cohort lifetime (MRR)
o	Defined as: Retained members at month t/Retained members at month t-1 
o	This metric changes across the months in the cohort lifetime
-	Commission Per Member Per Month (CMPM) 
o	This metric changes across the months in the cohort lifetime
-	Interest Rate (IR)
-	Member count for the cohort

Here is my LTV formula I wrote up: **(CMPM * MEMBER COUNT) * (MRR / (1+IR-MRR)) **

Explanation : 

Please note that as someone who has not worked in the healthcare industry, I cannot guarantee the accuracy of this formula. However, based on my research and understanding, it appears that the formula (CMPM * MEMBER COUNT) * (MRR / (1+IR-MRR)) can be used to estimate the lifetime value of a particular cohort, taking into account factors such as commission per member, retention rates, interest rates, and the number of members in the cohort. 

The first part, (CMPM * MEMBER COUNT), calculates the total revenue earned from the cohort. It multiplies the commission earned per member each month by the number of members in the cohort to get the total revenue earned over the cohort lifetime.

The second part, (MRR / (1+IR-MRR)), calculates the discount rate-adjusted retention rate for the cohort. It takes the monthly retention rate for the cohort and adjusts it for the time value of money using the interest rate. This calculates the probability that a customer will continue to use the service in the future, given the discount rate and retention rate.
Multiplying these two parts together gives you the estimated total value of the cohort over its lifetime.



**Part 2** 

The csv file has paying member historical data arranged by Policy_number from January 2015 to December 2019 with the following fields:

-	Start Date, Start Month and Churn Date of the policy
-	Number of members per policy 
-	Maximum duration that the plan allows 
-	State of the policy holder
-	Insurance carrier or provider of the policy 

In my analysis, I would like to analyze at cohort level and try to answer the following questions:

1.	Are there any factors that impact the length of member Lifetime? 
2.	What does Monthly Retention Curve look like? How about Cumulative Retention Curve? 

•	Cumulative Retention is defined as: Retained members at month t/Starting number of members at the beginning of a cohort’s life



-------------------------------------

* what is Retention Rate/Curve? 

Retention rate is an important metric that calculates the percentage of users who continue using your product or service over a given time period. A high retention rate means your current customers value your product and are providing a sustainable source of revenue. A low retention rate means you have a leaky bucket. No matter how many users you add through your acquisition strategy, they’ll keep churning, and you’ll keep losing money.            

-------------------------------------

* Relevant Files:

1) Retention Curve Project.ipynb

- Utilized Python programming language within a Jupyter Notebook environment.
- Developed the code for data analysis using various statistical approaches including IQR Method and Regression/Statistical Modeling techniques.
- Employed data visualization techniques with Matplotlib/Seaborn library to convey meaningful insights regarding the Cumulative/Normal Retention Rate/Curve.
- Presented the results in a clear and concise manner to facilitate easy interpretation and understanding of the findings.

2) PowerBI Visualization [Retention Curve Project].pbix

- Utilized PowerBI, a data visualization and business intelligence tool, to present the findings.
- Integrated various forms of valuable information, such as map and tree charts, to identify correlations between member lifetime and other relevant variables.
- Presented the analysis in a clear and concise manner to facilitate easy interpretation and understanding of the findings.

3) Mid-Atlantic SKU Selection Presentation.pptx
- Outlook summary of my findings and purpose of this project
- Summarized all the process I applied to this project (Statistical/Inferential/Descriptive Analysis)
- Included my personal thought on future improvement of this work for the future use

---------------------------------

Last but not least, please feel free to comment if you have any new idea to add on this project for the development.
Enjoy and let me know if you have any questions on my work.
