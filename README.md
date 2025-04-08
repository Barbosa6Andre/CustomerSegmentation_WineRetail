# Customer Segmentation – Wine Retail  
**A data analysis and best practices project focused on customer behavior and marketing strategy optimization for a Portuguese wine retailer.**

---

## 📌 Project Overview  
This project applies **data analysis best practices** to identify customer behavior patterns using transactional and demographic data from a wine store. The goal is to extract actionable insights that can guide future marketing strategies and improve segmentation.

---

## 🧠 Key Questions Explored  
- 💸 How does **income** influence total customer spending?  
- 👨‍👩‍👧 How do **dependents** (children and teenagers) affect purchase behavior?  
- 🥩 Which **product categories** contribute most to overall sales?  
- 🎓 How do **education** and **marital status** influence preferences?  
- 📣 How effective were past **marketing campaigns**?  
- 🛒 What are the primary **purchase channels** and what patterns emerge?

---

## 📊 Dataset Description  
The dataset used in this project is the [Customer Personality Analysis Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis), originally provided by **Dr. Omar Romero-Hernandez**.  

It contains customer-related data from a wine retailer and includes **demographic information**, **purchase history**, **channel preferences**, and **responses to marketing campaigns**.  

The data spans several categories:

### 🧍 People Attributes
- `ID`: Unique customer identifier  
- `Year_Birth`: Customer’s year of birth  
- `Education`: Highest education level  
- `Marital_Status`: Marital status (e.g., Married, Single, Together, Widow)  
- `Income`: Yearly household income  
- `Kidhome`: Number of children in the household  
- `Teenhome`: Number of teenagers in the household  
- `Dt_Customer`: Date of customer enrollment  
- `Recency`: Days since last purchase (lower = more recent)  
- `Complain`: 1 if the customer complained in the last 2 years, 0 otherwise  

### 🛍️ Product Spending Attributes
Spending (in monetary value) over the past 2 years on:
- `MntWines`: Wine  
- `MntFruits`: Fruits  
- `MntMeatProducts`: Meat products  
- `MntFishProducts`: Fish products  
- `MntSweetProducts`: Sweets  
- `MntGoldProds`: Gold products (e.g., jewelry, accessories)

### 📣 Promotion Attributes
- `NumDealsPurchases`: Purchases made using a discount  
- `AcceptedCmp1–5`: Whether the customer accepted campaigns 1 to 5  
- `Response`: Whether the customer accepted the last campaign  

### 🌐 Place & Channel Attributes
- `NumWebPurchases`: Purchases through the website  
- `NumCatalogPurchases`: Purchases via catalog  
- `NumStorePurchases`: In-store purchases  
- `NumWebVisitsMonth`: Number of website visits in the last month  

---

## 🔄 Project Outline  

0. **Setting Up the Coding Environment**  
   Prepare the necessary Python libraries and set up the data analysis environment.

1. **Data Cleaning**  
   Handle missing values, remove discrepancies, and preprocess data to prepare for analysis.

2. **Exploratory Data Analysis**  
   Investigate the dataset to uncover initial patterns, characteristics, and potential insights.

3. **Data Processing**  
   Normalize data, manage categorical variables through encoding, and prepare data for modeling.

4. **Conclusions**  
   Showcase final conclusions over all insights discovered during the project.

5. **Clustering and Classification** *(Future Step)*  
   Implement clustering to identify customer segments. Future steps will involve classification to predict customer behavior based on identified segments.

---

## 🧰 Technologies Used  
- `Python`  
- `Pandas`  
- `NumPy`  
- `Matplotlib`  
- `Seaborn`  

---

## 📈 Summary Insights  
- 💰 **Income levels** vary widely, providing opportunities for value-based segmentation  
- 👶 Households with more dependents tend to spend differently across product categories  
- 🍷 **Wine** stands out as the most purchased category  
- ❌ **Low campaign acceptance** rates signal opportunities for strategy adjustment  
- 🌐 Cross-channel behavior offers insights for future personalized campaigns  

---

Final Remarks

This project leverages data-driven insights to refine marketing strategies and product offerings, aligning them more closely with customer needs and behaviors. The insights derived will be used to inform future analytical efforts, including predictive modeling of customer behavior.

---

## 🧪 How to Run This Project  

1. Clone this repository  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt
   
