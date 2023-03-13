# RetentionCurveProject
#Healthcare #RetentionCurve #Python # Exploratory Data Analysis #Descriptive Statistics #Regression model # Inferential Statistics#Pandas #Matplotlib #Seaborn #Statsmodels #Jupyternoteboo

-------------------------------------

## General Outlook / Objectives

This project has been constructed with a Coholt Analysis for the case when a healthcare company (e.g. ) to analyze retention rate of the customers at the coholt level. 

Part 1 

Customer Life Time Value (LTV) is measured for each cohort, which consists of all members starting in a given calendar month. There are several metrics that impact LTV:  

-	Monthly Retention Rates across the cohort lifetime (MRR)
o	Defined as: Retained members at month t/Retained members at month t-1 
o	This metric changes across the months in the cohort lifetime
-	Commission Per Member Per Month (CMPM) 
o	This metric changes across the months in the cohort lifetime
-	Interest Rate (IR)
-	Member count for the cohort

Here is my LTV formula I wrote up: **(CMPM * MEMBER COUNT) * (MRR / (1+IR-MRR)) **



Part 2 

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

This project will be divided into four parts in order :

1) Macro-view Trend Analysis (Competitive/Geographical Analysis) -- US vs Mid-Atlantic
2) 5,000 SKU Selection on the basis of statistical approach
3) Categorial Proportion analysis in 5,000 SKU selection
4) Future Improvement & Strategical Planning

-------------------------------------

* Relevant Files:

1) Hana Project Visualization.pbix
- Used PowerBI as a visualization tool
- visualized the findings and analysis with a meaningful story from the reader's perspective
- First two slides heavily focus on the competitive analysis between US territory vs Mid-Atlantic area
- third/fourth slides are composed of all information what I have found from dataset in Mid-Atlantic area

2) Retail SKU Selection Project Python.py
- Used Jupyter Notebook
- Used IQR method to select the SKUs without violating categorical distribution trend (You can see the reason why I chose this method and how I applied to the item selection process in the ppt file, so please read if you are interested)
- Added visualization section with pieplot, barplot, lineplot, and donut chart

3) Mid-Atlantic SKU Selection Presentation.pptx
- Outlook summary of my findings and purpose of this project
- Summarized all the process I applied to this project (Statistical/Inferential/Descriptive Analysis)
- Included my personal thought on future improvement of this work for the future use

---------------------------------

Last but not least, please feel free to comment if you have any new idea to add on this project for the development.
Enjoy and let me know if you have any questions on my work.
