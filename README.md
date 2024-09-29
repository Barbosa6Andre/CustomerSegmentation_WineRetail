Marketing Campaign Analysis

Project Overview: Customer Personality Analysis

Technologies Used:

	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn

How to Run the Project:

	1.	Clone the repository.
	2.	Install necessary dependencies using requirements.txt.
	3.	Open the Jupyter notebook and follow the steps outlined for data cleaning and exploratory analysis.

Context

Customer Personality Analysis is a strategic approach used by companies to better understand their customers’ preferences and behaviors. By analyzing customer traits and buying habits, businesses can tailor their products and marketing strategies more effectively to various customer segments.

Problem Statement

This project employs unsupervised machine learning techniques to identify common behaviors across different customer segments, focusing on clustering to summarize customer segments and laying the groundwork for future classification of customer types.

Hypotheses and Assumptions:

	•	It is hypothesized that households with teens might show similar purchase behaviors to households with children, and that having more dependents might reduce disposable income for other expenditures.

Data Constraints:

	•	The analysis is constrained by the lack of data on gender identity, detailed campaign strategies, and specific product categories which could enhance customer profiling and product strategy.

Dataset Description

The dataset used is the Customer Personality Analysis dataset, sourced from Kaggle:
Customer Personality Analysis Dataset.

Provided by Dr. Omar Romero-Hernandez, the dataset includes attributes related to customer demographics, buying patterns, and interactions with marketing campaigns:

People Attributes

	•	ID: Customer’s unique identifier
	•	Year_Birth: Customer’s birth year
	•	Education: Customer’s education level
	•	Marital_Status: Customer’s marital status
	•	Income: Customer’s yearly household income
	•	Kidhome: Number of children in customer’s household
	•	Teenhome: Number of teenagers in customer’s household
	•	Dt_Customer: Date of customer’s enrollment with the company
	•	Recency: Number of days since customer’s last purchase
	•	Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Products Attributes

	•	MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds: Amount spent on respective products in the last 2 years

Promotion Attributes

	•	NumDealsPurchases: Number of purchases made with a discount
	•	Accepted Campaigns (1-5): Response to marketing campaigns
	•	Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

Place Attributes

	•	NumWebPurchases, NumCatalogPurchases, NumStorePurchases: Number of purchases made through respective channels
	•	NumWebVisitsMonth: Number of visits to company’s website in the last month

Project Steps

	0.	Setting Up the Coding Environment: Prepare the necessary Python libraries and set up the data analysis environment.
	1.	Data Cleaning: Handle missing values, remove discrepancies, and preprocess data to prepare for analysis.
	2.	Exploratory Data Analysis: Investigate the dataset to uncover initial patterns, characteristics, and potential insights.
	3.	Data Processing: Normalize data, manage categorical variables through encoding, and prepare data for modeling.
	4.	Clustering and Classification: Implement clustering to identify customer segments. Future steps will involve classification to predict customer behavior based on identified segments.

Key Questions Addressed

	•	Income vs. Total Expense Relationship: Exploring how customer income influences total expenses.
	•	Impact of Dependents: Analyzing the influence of having children and teenagers at home on total spending.
	•	Product Sales Importance: Determining the role of each type of product in total sales.
	•	Influences on Product Purchases: Investigating how education and marital status affect product purchases.
	•	Marketing Campaign Performance: Evaluating the effectiveness of different marketing campaigns.
	•	Purchasing Behavior: Examining customer behavior in relation to various types of purchases and web visits.

Initial Data Statistical Summary

	•	Income Variability: Wide range of customer income levels, from $1,730 to an outlier of $666,666.
	•	Age Utility: Converting Year_Birth to Age would provide more actionable insights.
	•	Promotional Response: Low acceptance rates for marketing campaigns suggest potential areas for improvement.

Final Remarks

This project leverages data-driven insights to refine marketing strategies and product offerings, aligning them more closely with customer needs and behaviors. The insights derived will be used to inform future analytical efforts, including predictive modeling of customer behavior.
