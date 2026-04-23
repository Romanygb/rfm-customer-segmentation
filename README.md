# 📊 RFM Customer Segmentation Analysis

Strategic customer segmentation using RFM (Recency, Frequency, Monetary) methodology to optimize marketing spend, improve retention, and maximize customer lifetime value.

## 🎯 Project Overview

- **Dataset:** Online Retail Dataset (541,909 transactions, 4,370 customers)
- **Tools:** Python, Pandas, SQL, PostgreSQL, Matplotlib, Seaborn
- **Analysis Type:** RFM segmentation with actionable business recommendations
- **Business Goal:** Identify high-value customers and at-risk segments for targeted interventions

## 🔍 Key Findings

### Customer Segments Identified

**Champions (951 customers - 22%)**
- Recent purchases, high frequency, high spending
- Top priority for retention and upselling

**Lost (910 customers - 21%)**
- Haven't purchased in months, low engagement
- Critical retention problem: 1:1 ratio with Champions

**Loyal Customers (483 customers - 11%)**
- Consistent purchasers with growth potential
- Prime candidates for Champion conversion

**At Risk (remaining segments)**
- Previously engaged customers showing decline
- Urgent intervention required

### Critical Business Insight

**The 1:1 Problem:** For every customer we retain as a Champion, we lose one completely. This indicates severe retention challenges requiring immediate action.

## 💡 Strategic Recommendations

### Immediate Priorities (Week 1-4)

**1. Save At-Risk Customers**
- Launch 48-hour win-back campaign
- 15% personalized discount offers
- Phone outreach for high-value accounts
- **Target:** Recover 30% of at-risk segment

**2. Activate Lost Customers**
- Conduct churn reason survey
- A/B test reactivation messaging
- Time-limited comeback offers
- **Target:** Reactivate 10% (90 customers)

**3. Reward Champions**
- VIP loyalty program launch
- Exclusive early access to products
- Dedicated support channel
- **Target:** +20% lifetime value increase

### Medium-Term Strategy (Month 2-3)

**4. Convert Loyal → Champions**
- Upgrade path with clear benefits
- Referral incentive program
- Purchase history recommendations
- **Target:** 25% conversion rate

**5. Nurture Promising Customers**
- Automated onboarding sequence
- Education about product value
- Second purchase incentive (30-day window)
- **Target:** Prevent Lost segment migration

### Expected Business Impact

**3-Month Targets:**
- Reduce Lost customers: 910 → 700 (-23%)
- Increase Champions: 951 → 1,100 (+15%)
- Overall retention improvement: +30%
- **Projected annual revenue impact: +$500K**

## 📈 Methodology

### RFM Scoring System

Each customer receives scores 1-5 on three dimensions:

**Recency (R):** Days since last purchase
- Score 5: Purchased within last week
- Score 1: No purchase in 6+ months

**Frequency (F):** Number of purchases
- Score 5: 20+ orders
- Score 1: Single purchase only

**Monetary (M):** Total lifetime spending
- Score 5: $5,000+ spent
- Score 1: Under $100 spent

### Segmentation Logic

Customers grouped by RFM combinations:
- **555 = Champions:** Best on all metrics
- **5XX = Loyal:** Recent buyers with growth potential
- **X5X = Frequent:** High engagement customers
- **1XX = Lost:** No recent activity

## 🛠️ Technical Skills Demonstrated

- **Advanced SQL:** CTE (WITH clauses), complex aggregations, date arithmetic
- **Customer Analytics:** RFM segmentation, cohort analysis, retention metrics
- **Python Programming:** Custom segmentation functions, conditional logic, data transformation
- **Statistical Methods:** Quintile-based scoring, distribution analysis
- **Data Visualization:** Multi-segment scatter plots, revenue analysis charts
- **Business Intelligence:** Translating analytics into revenue-focused strategies with measurable KPIs

## 📁 Project Files

- `RFM_Customer_Segmentation.ipynb` - Complete analysis with visualizations and recommendations
- `rfm_segments.csv` - Customer segments with RFM scores

## 📫 Contact

**Roman** | [GitHub](https://github.com/Romanygb)

---

## 🔗 Related Projects

- [Superstore Sales Analysis](https://github.com/Romanygb/superstore-sales-analysis) - Exploratory data analysis
- [Cohort Retention Analysis](https://github.com/Romanygb/cohort-retention-analysis) - Customer retention patterns

---

*Part of my Data Analyst portfolio demonstrating customer segmentation expertise and strategic business thinking*
