# Consumer Behavior Insights

A comprehensive data analysis project exploring e-commerce consumer behavior patterns through statistical analysis and data visualization.

### Results

- **Income-Category Spending Patterns**: Identified distinct spending behaviors across income levels and product categories
- **Digital Influence Impact**: Social media influence varies significantly across age groups, with unique patterns for each demographic
- **Customer Segmentation**: High-value customers distinguished by behavioral patterns beyond simple spending metrics
- **No Gender-Income Bias**: Statistical analysis (chi-square test) reveals no significant relationship between gender and income level

### Stack

- **Python 3.10** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **SciPy** - Statistical analysis
- **Jupyter Notebook** - Interactive analysis environment

## Analysis & Visualizations

### Figure 1: Purchase Amount by Income Level and Product Category
Understanding how different income levels spend across product categories reveals key market segments and pricing opportunities.

![Purchase Amount by Income and Category](viz/Fig1-Purchase%20Amount%20by%20Income%20and%20Category.png)

---

### Figure 2: The Digital Influence Spectrum
Social media's impact on purchasing behavior varies significantly across age groups, providing insights for targeted digital marketing strategies.

![Social Media Influence by Age](viz/Fig2-Social%20Media%20Influence%20by%20Age.png)

---

### Figure 3: Purchase Profile by Product Category
Analyzing purchase volume and average spending by category helps identify high-value segments and optimize inventory strategies.

![Purchase Profile by Category](viz/Fig3-Purchase%20Profile%20by%20Category.png)

---

### Figure 4: Gender and Income Level Distribution
Statistical analysis reveals the relationship between gender and income level, with chi-square testing showing no significant correlation.

![Gender and Income Distribution](viz/Fig4-Gender%20and%20Income%20Distribution.png)

---

### Figure 5: Income-Demographics Spending Heatmap
The intersection of income and education levels reveals nuanced spending patterns across demographic segments.

![Income and Education Spending](viz/Fig5-Income%20and%20Education%20Spending.png)

---

### Figure 6: Customer Value Segmentation
Behavioral profiling distinguishes high-value from low-value customers beyond simple spending metrics, enabling sophisticated retention strategies.

![Customer Value Segmentation](viz/Fig6-Customer%20Value%20Segmentation.png)

## Dataset
Consumer Behavior was obtained from [Kaggle](https://www.kaggle.com/datasets/salahuddinahmedshuvo/ecommerce-consumer-behavior-analysis-data).
> This dataset provides a comprehensive collection of consumer behavior data that can be used for various market research and statistical analyses. It includes information on purchasing patterns, demographics, product preferences, customer satisfaction, and more, making it ideal for market segmentation, predictive modeling, and understanding customer decision-making processes. -- Kaggle

### Columns Overview

| Column Name | Description | Type |
|------------|-------------|------|
| **Customer_ID** | Unique identifier for each customer | String |
| **Age** | Customer's age | Integer |
| **Gender** | Customer's gender | Categorical: Male, Female, Non-binary, Other |
| **Income_Level** | Customer's income level | Categorical: Low, Middle, High |
| **Marital_Status** | Customer's marital status | Categorical: Single, Married, Divorced, Widowed |
| **Education_Level** | Highest level of education completed | Categorical: High School, Bachelor's, Master's, Doctorate |
| **Occupation** | Customer's occupation | Categorical: Various job titles |
| **Location** | Customer's location | String: City, region, or country |
| **Purchase_Category** | Category of purchased products | Categorical: Electronics, Clothing, Groceries, etc. |
| **Purchase_Amount** | Amount spent during the purchase | Decimal |
| **Frequency_of_Purchase** | Number of purchases made per month | Integer |
| **Purchase_Channel** | The purchase method | Categorical: Online, In-Store, Mixed |
| **Brand_Loyalty** | Loyalty to brands | Scale: 1-5 |
| **Product_Rating** | Rating given by the customer to a purchased product | Scale: 1-5 |
| **Time_Spent_on_Product_Research** | Time spent researching a product | Integer: Hours or minutes |
| **Social_Media_Influence** | Influence of social media on purchasing decision | Categorical: High, Medium, Low, None |
| **Discount_Sensitivity** | Sensitivity to discounts | Categorical: Very Sensitive, Somewhat Sensitive, Not Sensitive |
| **Return_Rate** | Percentage of products returned | Decimal |
| **Customer_Satisfaction** | Overall satisfaction with the purchase | Scale: 1-10 |
| **Engagement_with_Ads** | Engagement level with advertisements | Categorical: High, Medium, Low, None |
| **Device_Used_for_Shopping** | Device used for shopping | Categorical: Smartphone, Desktop, Tablet |
| **Payment_Method** | Method of payment used for the purchase | Categorical: Credit Card, Debit Card, PayPal, Cash, Other |
| **Time_of_Purchase** | Timestamp of when the purchase was made | Date/Time |
| **Discount_Used** | Whether the customer used a discount | Boolean: True/False |
| **Customer_Loyalty_Program_Member** | Whether the customer is part of a loyalty program | Boolean: True/False |
| **Purchase_Intent** | The intent behind the purchase | Categorical: Impulsive, Planned, Need-based, Wants-based |
| **Shipping_Preference** | Shipping preference | Categorical: Standard, Express, No Preference |
| **Payment_Frequency** | Frequency of payment | Categorical: One-time, Subscription, Installments |
| **Time_to_Decision** | Time taken from consideration to actual purchase | Integer: Days |

## Setup Instructions

### Prerequisites
  - Anaconda or Miniconda installed on your system
  - Have `python3` installed

### Environment Setup
Create the conda environment from the environment file:
```bash
conda env create -f environment.yml
```
Activate the environment:
```bash
conda activate consumerAnalytics
```