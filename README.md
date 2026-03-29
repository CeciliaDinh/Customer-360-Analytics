# 🧠 Customer 360 Analytics  
### RFM, Churn & Growth Insights using Python & PySpark  
**Author:** Dinh Thi Thanh Hang  

---

## 🚀 Project Overview

This project leverages **Python and PySpark** to perform a **full-scale customer analytics** on retail transactional data. The goal is to uncover:

- Customer behavior patterns  
- Churn drivers  
- Product preferences  
- Geographic growth opportunities  

Analysis is structured using the **3P-G Framework**:

> **Product – People – Place – Growth**  

This allows translating raw data into **actionable business strategies** that optimize revenue, retention, and growth.

---

## 🧩 Problem Statement

Despite healthy revenue, the business faces multiple challenges:

- ⚠️ High **churn (~32%)**  
- 🇬🇧 Over-dependence on the **UK market**  
- 🎯 Weak **customer retention programs**  
- 📉 Revenue highly **seasonal** (holiday-driven spikes)  
- 🧾 Data quality issues (missing or inconsistent country data)

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **PySpark** (distributed data processing & scalability)  
- **RFM Analysis** for customer segmentation  
- **K-Means Clustering** for behavior-based personas  
- **EDA & Visualization** for actionable insights  

---

## 🧠 Analytical Framework

| Dimension | Key Question |
|----------|-------------|
| **Product** | What products are driving sales and growth? |
| **People** | Who are the active and churned customers? |
| **Place** | Which countries/markets generate the most revenue and churn? |
| **Growth** | How can the business scale while retaining high-value customers? |

---

# 🔍 Key Insights

---

## 👥 Customer Behavior (RFM)

| Metric | Active Customers | Churned Customers |
|--------|----------------|-----------------|
| Recency | 16 days | 197 days |
| Frequency | 390 purchases | 2.3 purchases |
| Monetary | $422,701 | $963 |

💡 **Takeaways:**
- Churned customers mostly make **one-time purchases**  
- Active customers generate **~438x more revenue**  
- Retention is the **primary lever for growth**

---

## 🛍️ Product Insights

### 🎯 Customer Preferences
- Vintage / retro-style items  
- Seasonal & holiday products (Christmas, weddings, etc.)  
- Personalized lifestyle items (mugs, décor, gifts)  

**Insight:** Customers buy **emotion-driven products**, not just utility.

### 🏆 Top-Selling Products
- **PAPER CRAFT, LITTLE BIRDIE** (>80,000 units sold)  
- Popular items include **ceramics, decorative jars, and office gadgets**  

**Observation:** Some top-selling items are also purchased by churned customers → indicates **potential product or quality issues**.

---

## 🎉 Seasonal & Occasion Products

**Key Insight:**
- Specialized products for **holiday events** (e.g., Christmas) are **growing rapidly**  
- Rising interest in **souvenirs, gifts, and wedding cards**  

**Actionable Recommendations:**
- Launch **seasonal campaigns** timed for key holidays  
- Promote **limited-edition bundles**  
- Offer **personalization options** to increase retention and repeat purchases  

---

## 🌍 Geographic Insights

### 🇬🇧 United Kingdom
- Largest market (~3,900 customers)  
- Main revenue driver  
- ⚠️ ~1/3 churn rate → retention risk  

### 🌎 Market Overview

| Category | Countries |
|----------|----------|
| 🚀 High Growth | Channel Islands, Australia |
| 🟢 Stable (Low Churn) | Germany, Norway, Finland, Spain |
| ⚠️ High Churn (Small Base) | Greece, Canada, Bahrain |
| ❗ Data Issues | Singapore, Saudi Arabia, Lithuania |

💡 **Observation:** Business is heavily driven by **seasonality and event-based demand**

---

## 📈 Growth Insights

- UK shows strong **holiday spikes**  
- Other markets have **plateau or slow growth patterns**  
- Emerging markets only started purchasing after 2011  

**Takeaway:** Focus growth strategy on **high-potential countries** and **seasonal product promotions**

---

## 🧬 Customer Segmentation

### Behavior-Driven Personas (Clustering)

| Segment | Description | Strategy |
|--------|------------|----------|
| 🟡 One-Time Buyers | Low engagement, high churn | Onboarding & reactivation campaigns |
| 🟢 Loyal Customers | High frequency, monetary value | Loyalty programs, VIP perks |
| 🔵 Discount Hunters | Purchase only on promotion | Limit discount abuse, flash sales |
| 🟣 New High-Potential | Recent activity, no discounts | Early engagement, welcome kits |

---

# 🚨 Core Business Problems

- High **churn**  
- Over-reliance on **UK market**  
- Weak **customer lifecycle programs**  
- Seasonality-dependent revenue  
- **Product quality risks**  
- Inconsistent **data quality**

---

# 🚀 Strategic Recommendations

### 🎯 Retention
- Launch **loyalty programs**  
- Personalized campaigns based on **RFM & personas**  
- Post-purchase engagement and follow-ups  

### 🛍️ Product Strategy
- Focus on **seasonal and high-demand products**  
- Improve **packaging and delivery quality**  
- Bundle complementary items to increase **average order value (AOV)**  

### 🌍 Market Expansion
- Scale **high-growth markets** (Australia, Channel Islands)  
- Consolidate **stable EU markets** with low churn  

### 💡 Promotions
- Reduce deep discounts  
- Offer **value-added bundles**, personalization, and rewards  

### 📊 Data Quality
- Clean missing/inconsistent country data  
- Standardize tracking for reliable insights  

---

# 🔮 Future Work

- Build **churn prediction model** (ML)  
- Implement **recommendation system** for personalized marketing  
- Create **interactive dashboard** for real-time insights  
- Model **Customer Lifetime Value (CLV)**  

---

# 📌 Key Takeaway

> The biggest opportunity is not acquisition —  
> **it’s converting one-time buyers into loyal customers**.

---

## ⭐ Highlights

- End-to-end **data analytics workflow**  
- Strong **business storytelling**  
- Scalable **PySpark implementation**  
- Actionable insights for **retention, product, and market strategy**

---

## 📬 Contact

Reach out for collaboration or discussion!
