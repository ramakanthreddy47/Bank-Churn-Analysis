<img width="1285" height="725" alt="Screenshot 2025-12-25 185054" src="https://github.com/user-attachments/assets/b9fffdf5-5d76-477c-a50e-ea6e76aba298" />

📊 Bank Churn Analysis | Power BI
🔍 Project Overview

This project analyzes bank customer churn to identify key factors influencing why customers leave the bank. Using multiple customer-related datasets, the dashboard provides actionable insights to support retention strategies, loyalty programs, and business decision-making.

The analysis focuses on demographics, financial behavior, product usage, and customer activity to highlight churn patterns and high-risk customer segments.

📂 Data Sources

The model integrates data from the following tables:

-CustomerInfo

-Bank_Churn

-ActiveCustomer

-CreditCard

-ExitCustomer

-Gender

-Geography

Each table contributes attributes such as credit score, age, tenure, balance, product count, activity status, and churn flag.

🔧 Key Data Transformations (Power Query)

The following transformations were applied to prepare clean, analysis-ready data:

-Removed non-impact columns (RowNumber, Surname)

-Converted data types (dates, numeric, categorical fields)

-Created Credit Score Bands
    (Excellent, Very Good, Good, Fair, Poor)

-Standardized binary flags
    (HasCrCard, IsActiveMember, Exited → Yes/No labels)

-Cleaned and validated Bank DOJ (Date of Joining)

-Merged lookup tables for Gender and Geography

-Handled nulls and inconsistencies

-Built a star-schema friendly model for performance

📈 Analysis & Insights

-Customers with lower credit scores, lower balances, and fewer products show higher churn

-Inactive members are significantly more likely to exit

-Geography and age groups influence churn behavior

-Customers holding credit cards are more likely to be retained

-Long-tenure customers demonstrate higher loyalty

🛠 Tools & Skills Used

-Power BI

-Power Query (ETL)

-Data Modeling

-DAX Measures

-Business Requirement Analysis

-Dashboard Design & Storytelling

🎯 Business Value

The dashboard helps stakeholders:

-Identify high-risk churn customers

-Understand drivers of churn

-Support targeted retention campaigns

-Improve customer lifetime value








