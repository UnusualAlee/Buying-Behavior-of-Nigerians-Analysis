# Behavioral/Digital & Social Media analysis

### 🎯 Project Overview

This data project aims to provide insight into how Nigerians make purchase decisions. By analyzing various aspect such as; their income, where they shop, what product is often bought, how often they shop, how much they spend on average, preferred payment method and what influences their buying decisions. We seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the Buying Behavior of Nigerians.

### 🧩 Data Source

The primary dataset for this analysis is the "Form_Response.csv" file, collected through a Google Form and contains detailed information about each respondents buying behavior.

### 🛠️ Tools

- Power Query - Clean data, prepare data.
- Excel - Create additional column, performed calculations using formulas.
- Pivot Table - Analyze and Summarize data, Build Dashboard.


###  Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks;
1. Data loading and inspection.
2. Removing duplicates.
3. Handling missing values.
4. Data cleaning and formatting.

### Exploratory Data Analysis

- Total Respondents.
- Average shopping frequency.
- Average monthly spend.
- Top shopping platform.
- Most preferred payment method.
- Top decision influencing factor.

### Data Analysis

```excel
Monthly Spend category    =IF([@[Average Spend (#)]]<2000,"Low", IF([@[Average Spend (#)]]<=5000,"High"))
Active Shopper     =IF([@[Shopping Frequency (Per month)]]>=5,"Frequent","Occasional")
````

### 📊 Results/Findings

We had a total of 112 respondents, which reduced to 107 after data cleaning. The ages of the respondents ranged from 18–25, 26–35, and 36+. The sample cut across 15 states, with Lagos having the highest number of respondents (71), while Enugu, Rivers, Bayelsa, Kaduna, Imo, and Ondo had the least, with one respondent each.
The gender distribution of the sampled population shows that the majority of the respondents were male, with 64 males and 43 females, representing approximately 60% and 40% of the population respectively.
The average shopping frequency was three times per month, with an average minimum spending of ₦100,000. This indicates that most respondents fall within the high-income bracket.
WhatsApp emerged as the most preferred shopping channel, followed by physical stores, with the majority of respondents adopting bank transfers as their preferred payment option.
Quality emerged as the most significant factor influencing buyers’ decisions, as respondents tend to place strong value on the quality of the items they purchase. Discount Followed closely highlighting the fact that as much as respondents are willing to spend, they are equally looking to save. The fact that most purchased products are food and groceries underscores the essential nature of these basic necessities.

### Recommendation 

1. Businesses should leverage WhatsApp as the Primary Sales Channel
2. Businesses should focus on Quality as the Core Value by Introducing a quality assurance guarantee.
3. Use of  Discount-Based Strategies to drive sales.
4. Run advertisements to expand reach in the states like Enugu, Rivers, Bayelsa, Kaduna, Imo, and Ondo have only one respondent each.
