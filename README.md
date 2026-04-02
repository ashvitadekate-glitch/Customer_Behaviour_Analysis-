
## 📊 Customer Shopping Behavior Analysis

**End-to-end data analytics project analyzing customer behavior to uncover revenue drivers, optimize marketing strategies, and improve customer retention.**

---

## 🚀 Business Problem

A leading retail company is experiencing **shifts in customer purchasing behavior** across demographics, product categories, and sales channels. These changes are impacting **sales performance, customer satisfaction, and long-term loyalty**.

The business lacks clear visibility into:

* What drives **customer purchase decisions**
* Which factors influence **repeat buying behavior**
* How elements like **discounts, reviews, seasons, and shipping preferences** impact sales

### 🎯 Core Business Question:

> *How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?* 

---

## 🎯 Objective

* Analyze customer behavior across demographics and purchase patterns
* Identify key drivers of **revenue and repeat purchases**
* Segment customers into actionable groups (loyal, returning, new)
* Deliver **data-driven strategies** to improve engagement and profitability

---
## 📈 Key Insights

* 💰 **Revenue Imbalance:** Male customers generate **2.1x higher revenue** than females
* 🛍️ **Category Leader:** Clothing dominates both revenue (~$100K) and sales volume
* 🔁 **Customer Loyalty:** ~80% customers fall under the “loyal” segment
* 📉 **Subscription Opportunity:** Only ~27% customers are subscribed → growth potential
* 🏷️ **Discount Dependency:** Certain products rely heavily on discounts (up to 50%)
* 👥 **High-Value Segment:** Young adults contribute the highest revenue (~$62K) 

## 📁 Dataset Overview

* **Total Records:** 3,900 transactions 
* **Features:** 18 columns including demographics, purchase details, and behavior 
* **Key Variables:**

  * Age, Gender, Subscription Status
  * Category, Purchase Amount, Season
  * Discount Applied, Shipping Type, Review Rating
* **Data Cleaning:**

  * Handled 37 missing values in review ratings using median imputation 

---

## 🛠️ Tools & Technologies

* **Python (Pandas, NumPy)** – Data Cleaning & Feature Engineering
* **SQL (PostgreSQL)** – Business Querying & Analysis
* **Power BI** – Dashboard & Data Visualization
* **Excel** – Data Handling

---

## ⚙️ Methodology

### 1. Data Preparation (Python)

* Cleaned and transformed raw dataset
* Standardized columns for consistency
* Performed feature engineering:

  * Created `age_group` for segmentation
  * Derived `purchase_frequency_days`
* Loaded processed data into PostgreSQL for analysis 

---

### 2. Business Analysis (SQL)

Executed structured queries to solve business problems:

* Revenue contribution by gender
* Subscription vs non-subscription analysis
* Customer segmentation (New, Returning, Loyal)
* Discount impact on purchasing behavior
* Product performance & ratings
* Revenue distribution by age groups 

---

### 3. Visualization (Power BI)

Developed an interactive dashboard to monitor:

* Customer base and average purchase value
* Revenue & sales distribution by category
* Subscription behavior insights
* Age-group-based revenue trends

---

<img width="1265" height="687" alt="dashboard img" src="https://github.com/user-attachments/assets/33dc6507-3279-4681-8564-36fa4dd1072d" />


---

## 💡 Business Recommendations

* 📈 **Increase Subscription Adoption:** Introduce incentives and exclusive benefits
* 🎯 **Target High-Value Segments:** Focus on young adults and repeat buyers
* 🎁 **Strengthen Loyalty Programs:** Convert returning users into loyal customers
* 💸 **Optimize Discount Strategy:** Reduce over-dependence on discounts
* 🛒 **Improve Product Positioning:** Promote high-rated and top-selling products

---

## 📌 Project Highlights

* Solves a **real-world business problem using data**
* End-to-end pipeline: **Python → SQL → Power BI**
* Strong focus on **decision-making and business impact**
* Demonstrates **analytical + strategic thinking**

---
Understood—you want the **same structured style but cleaner and slightly refined (not messy, not too long)**. Here’s your polished version:

---

## 🛠️ How to Use This Project

**1. Clone the Repository**

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```
**2. Open Jupyter Notebook**

* `EDA.ipynb`
* Perform:
  * Data import & exploration
  * Data cleaning
  * Feature engineering
  * Database connection

**3. Load Data into SQL**
* Create a database (PostgreSQL/MySQL)
* Run Python code to load cleaned data

**4. Run SQL Analysis**
* Open `SQL query.sql`
* Execute queries to answer business questions

**5. Power BI Dashboard**
* Open `.pbix` file
* Connect to SQL database
* Explore interactive dashboard

**6. Reporting**
* Review project report & presentation for insights

---
## 🔗 Conclusion

This project showcases how data analytics can be used to **translate customer behavior into actionable strategies**, enabling businesses to improve **marketing efficiency, customer retention, and revenue growth**.



