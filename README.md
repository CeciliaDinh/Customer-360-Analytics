# 🧠 Customer 360 Analytics
### RFM, Churn & Growth Insights using Python & PySpark
**Author:** Dinh Thi Thanh Hang

---

## 🚀 Project Overview

This project leverages **Python and PySpark** to perform full-scale customer analytics on retail transactional data. The objective is to translate raw data into actionable business strategies that optimize revenue, retention, and geographic expansion. 

The analysis is structured using the **3P-G Framework**:
> **Product – People – Place – Growth**

---

## 🧩 Problem Statement

Despite healthy topline revenue, the business faces critical bottlenecks that threaten long-term profitability:
* ⚠️ **High Churn Risk (~32%)**
* 🇬🇧 **Geographic Over-reliance** on the UK market
* 🎯 **Weak Retention Mechanisms** failing to convert first-time buyers
* 📉 **Revenue Volatility** driven by highly seasonal spikes
* 🧾 **Data Quality Gaps** (missing or inconsistent regional tracking)

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy, Matplotlib, Seaborn) for exploratory analysis
* **PySpark** for distributed data processing and scalability
* **RFM Analysis** for quantifiable customer valuation
* **K-Means Clustering** for behavior-based persona modeling

---

## 🧠 Analytical Framework

| Dimension | Key Business Question |
|----------|-------------|
| **Product** | Which inventory drives baseline sales vs. seasonal spikes? |
| **People** | What behaviors separate high-LTV loyalists from churned users? |
| **Place** | Which regions offer the highest ROI and lowest churn? |
| **Growth** | How can we scale acquisition while plugging the "leaky bucket" of churn? |

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
* Churned users typically abandon the brand after just **1 to 2 purchases**.
* Retained, active customers generate **~438x more revenue**.
* **Business Impact:** Retention, not acquisition, is the primary lever for sustainable growth.

---

## 🛍️ Product Insights

### 🎯 Customer Preferences
* Strong demand for unique, niche décor (vintage/retro aesthetics).
* High volume in personalized lifestyle items and seasonal/holiday merchandise.

### 🏆 Top-Selling Products & Hidden Risks
* **Top Performer:** "PAPER CRAFT, LITTLE BIRDIE" (>80,000 units sold).
* **The Quality Paradox:** Stock Code **23166** is a best-seller, but frequently appears in the baskets of *churned* customers. 
* **Business Impact:** Because many top items are fragile/decorative, this correlation strongly suggests shipping damage or quality control issues are actively driving customers away.

---

## 🎉 Seasonal & Occasion Products

**Key Insight:**
Specialized products for holiday events, souvenirs, and weddings are growing rapidly. 

**Actionable Recommendations:**
* Shift marketing spend toward targeted **seasonal campaigns** prior to key holidays.
* Protect profit margins by offering **limited-edition bundles** and personalization rather than relying on deep discounts.

---

## 📈 YoY (Year-Over-Year) Growth

| Country | YoY Growth | Strategic Outlook |
|---------|------------|-------|
| Channel Islands | +72,425% | Hyper-growth market; allocate acquisition budget here. |
| Australia | +60,724% | Massive scale (reaching $90M); prime for expansion. |
| Austria | +2,403% | Moderate growth; requires targeted retention efforts. |
| Denmark | +1,406% | Moderate, stable growth. |
| Ireland (EIRE) | +1,723% | Steady; monitor customer feedback closely. |
| Bahrain | -99.58% | Stagnant/frozen market. |
| Brazil, Canada, EU | N/A (Started 2011) | Early-stage emerging markets. |

💡 **Observation:** Certain markets are exhibiting massive, explosive growth (Australia), signaling a clear path to diversify revenue away from UK dependence.

---

## 🌍 Churn Rate by Countries

| Country | Customer Base | Churn Insights |
|---------|---------------|----------------|
| United Kingdom | ~3,900 users | Main revenue driver, but suffers a massive **~33% churn rate**. |
| Finland, Norway, Germany | Mid-size markets | Low overall churn, but high drop-off after the 1st/2nd purchase. |
| Austria, Channel Islands | Small/Mid-size | Notable churn despite strong baseline growth. |
| Greece, Canada, Bahrain | 1–3 active users | Highly volatile; likely data outliers. |
| Singapore, Saudi Arabia | Missing data | NaN churn rates indicate tracking failures. |

💡 **Takeaway:** A one-size-fits-all retention strategy will fail. Tactics must be localized, prioritizing high-growth or high-churn regions.

---

## 🧬 Customer Segmentation (Clustering)

| Segment | Behavior Profile | Recommended Strategy |
|--------|------------|----------|
| 🟡 **One-Time Buyers** | Low engagement, high flight risk. | Automated onboarding & reactivation campaigns. |
| 🟢 **Loyal Customers** | High frequency, top revenue drivers. | VIP perks, early-access, and referral programs. |
| 🔵 **Discount Hunters** | High price sensitivity. | Limit discount abuse; leverage flash sales to clear inventory. |
| 🟣 **New High-Potential** | Recent activity, full-price buyers. | Welcome kits to secure the crucial second purchase. |

---

# 🚀 Strategic Recommendations

### 🎯 Retention
* Deploy automated post-purchase workflows targeting the "One-Time Buyer" segment to secure their 2nd and 3rd purchases.
* Launch a tiered VIP loyalty program for high-RFM customers.

### 🛍️ Product Strategy
* **Urgent:** Audit the supply chain, packaging, and QA for fragile top-sellers (like Stock Code 23166) to stop product-driven churn.
* Bundle complementary decorative items to increase Average Order Value (AOV).

### 🌍 Market Expansion
* Aggressively scale marketing spend in hyper-growth markets (Australia, Channel Islands).
* Consolidate market share in stable EU regions that exhibit naturally lower churn rates.

### 📊 Data Quality
* Standardize regional tracking and clean missing geographic data to ensure future analytics are built on a reliable foundation.

---

# 🔮 Future Work

* Deploy a **Machine Learning Churn Prediction Model** to proactively flag at-risk customers.
* Build a **Recommendation Engine** for targeted cross-selling.
* Develop an **Interactive Executive Dashboard** to monitor Customer Lifetime Value (CLV) in real-time.

---

# 📌 Key Takeaway

> The most profitable business opportunity is not top-of-funnel acquisition —  
> **it’s fixing the leaky bucket and converting one-time buyers into lifelong loyalists.**

---

## ⭐ Highlights

* End-to-end **data analytics workflow** * Strong **business storytelling and ROI focus**
* Scalable **PySpark implementation** for large datasets
* Actionable, data-backed strategies for **retention, product optimization, and market expansion**

---

## 📬 Contact

Reach out for collaboration or discussion!
