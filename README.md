# Customer-Segmentation-Analysis
Customer behavior and segmentation analysis using Python, exploring shopping patterns, satisfaction, cart abandonment, and recommendation effectiveness.
# Customer Segmentation & Analysis

## 📌 Project Overview

This project focuses on analyzing customer shopping behavior and identifying meaningful customer segments based on their purchasing patterns, satisfaction levels, browsing behavior, and interactions with the shopping platform.

The analysis uses customer survey and behavioral data to understand how customers search for products, interact with recommendations, complete or abandon purchases, and perceive their overall shopping experience.

The objective is to identify behavioral patterns and derive actionable insights that can help improve customer satisfaction, conversion, and the overall shopping experience.

---

## 🎯 Objectives

- Analyze customer shopping and browsing behavior
- Understand customer satisfaction levels
- Identify different customer segments based on behavioral patterns
- Analyze factors influencing cart abandonment
- Evaluate customer interaction with product recommendations
- Understand customer preferences and shopping patterns
- Generate actionable business insights from customer behavior

---

## 📊 Dataset

The dataset contains customer survey and shopping behavior information.

### Key Attributes

The dataset includes variables related to:

- Product search behavior
- Browsing duration
- Device used for shopping
- Search frequency
- Use of filters
- Search result exploration
- Product reviews
- Add-to-cart behavior
- Cart completion
- Cart abandonment factors
- Save-for-later behavior
- Recommendation helpfulness
- Recommendation rating accuracy
- Shopping satisfaction
- Service appreciation
- Areas requiring improvement

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Exploratory Data Analysis**
- **Customer Segmentation**
- **Statistical Analysis**

---

## 🧹 Data Preparation

The dataset was inspected and prepared before analysis.

Key data preparation activities included:

- Identifying missing values
- Examining categorical and numerical variables
- Understanding the distribution of customer responses
- Handling missing values appropriately
- Checking customer behavior patterns across different variables

The `Product_Search_Method` variable contained **149 missing values**. Rather than removing a large portion of the dataset, missing values were retained/handled appropriately during analysis.

---

## 🔍 Analysis Performed

### 1. Customer Demographic Analysis

Customer demographics were analyzed to understand the composition of the dataset.

The middle 50% of customers were between approximately **18 and 53 years old**.

Gender distribution was also examined, with males representing the largest gender group at **26.63%**.

---

### 2. Shopping Behavior Analysis

Customer interactions with the shopping platform were analyzed across different behavioral dimensions, including:

- Search frequency
- Browsing duration
- Product filtering
- Search result exploration
- Product reviews
- Add-to-cart activity
- Save-for-later behavior
- Purchase completion

This helped identify differences in how customers interact with the platform during their shopping journey.

---

### 3. Customer Satisfaction Analysis

Customer satisfaction was analyzed to identify potential issues in the overall shopping experience.

A key finding was that **40% of respondents reported low shopping satisfaction**, indicating a significant opportunity to improve the customer experience.

---

### 4. Cart Abandonment Analysis

Different reasons for cart abandonment were analyzed to understand why customers did not complete purchases.

One of the major findings was that **27.38% of respondents cited better pricing elsewhere** as a reason for abandoning their carts.

Other factors, including shipping-related concerns, were also examined.

---

### 5. Recommendation Analysis

Customer perceptions of product recommendations were analyzed based on:

- Recommendation helpfulness
- Rating accuracy
- Customer interaction with recommendations

The analysis found that **67.38% of customers considered recommendations only sometimes helpful or not helpful**, highlighting an opportunity to improve recommendation relevance.

---

### 6. Customer Segmentation

Customers were analyzed based on combinations of behavioral characteristics such as:

- Shopping frequency
- Satisfaction
- Browsing behavior
- Purchase behavior
- Interaction with recommendations

The analysis identified distinct customer behavior patterns that can be used to understand different customer needs and engagement levels.

---

## 📈 Key Findings

- **40%** of respondents reported low shopping satisfaction.
- **27.38%** cited better pricing elsewhere as a reason for cart abandonment.
- **67.38%** of customers found recommendations only sometimes helpful or not helpful.
- The largest identified customer segment represented **17.25%** of customers and was characterized by **medium shopping frequency and low satisfaction**.
- Customer behavior varied considerably across shopping frequency, satisfaction, browsing, and purchase-related activities.

---

## 💡 Business Insights

The analysis highlights several areas where an e-commerce platform can improve customer experience and conversion.

### Pricing

Since better pricing elsewhere was a major reason for cart abandonment, competitive pricing and targeted offers can help reduce purchase drop-offs.

### Customer Satisfaction

The presence of a large low-satisfaction customer group indicates the need to identify and address the specific aspects of the shopping experience causing dissatisfaction.

### Recommendations

A significant proportion of customers did not find recommendations consistently helpful. Improving recommendation relevance and personalization could increase customer engagement.

### Customer Segmentation

Different customer behavior patterns suggest that customers should not be treated as a single group. Segment-specific strategies can help improve engagement and customer experience.

---

## 📂 Project Structure

```text
Customer-Segmentation-and-Analysis/
│
├── Customer_Segmentation_Analysis.ipynb
└── README.md
