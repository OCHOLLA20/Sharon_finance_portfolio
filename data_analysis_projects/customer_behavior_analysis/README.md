# Customer Behavior Analysis

## Overview
Deep dive customer analytics using RFM analysis, segmentation, and behavioral pattern recognition to drive targeted marketing strategies.

## Files
- `behavior_analysis.ipynb` - Complete customer analysis workflow
- `segmentation_model.py` - Customer segmentation algorithms
- `customer_transactions.csv` - Anonymized transaction dataset (50K customers)
- `insights_report.pdf` - Business insights and recommendations

## Analysis Framework
### 🎯 **RFM Analysis**
- **Recency**: Days since last purchase
- **Frequency**: Number of transactions per period
- **Monetary**: Total spend per customer
- **Segmentation**: 11 distinct customer segments identified

### 👥 **Customer Segments**
1. **Champions** (5.2%): High value, frequent, recent buyers
2. **Loyal Customers** (12.8%): Regular buyers with high lifetime value
3. **Potential Loyalists** (18.3%): Recent customers with potential
4. **New Customers** (8.7%): Recent first-time buyers
5. **Promising** (7.1%): Recent buyers with moderate spend
6. **Need Attention** (9.4%): Above average but declining engagement
7. **About to Sleep** (15.2%): Declining frequency and recency
8. **At Risk** (11.1%): Previously good customers now at risk
9. **Cannot Lose Them** (3.8%): High value but haven't purchased recently
10. **Hibernating** (6.9%): Low spend, low frequency, low recency
11. **Lost** (1.5%): Haven't purchased in 12+ months

## Key Insights
### 💰 **Revenue Distribution**
- **Top 20%** of customers generate **68%** of total revenue
- **Champions** segment: $2,400 average annual value
- **At Risk** segment: $890 average (retention opportunity)
- **Customer Lifetime Value**: $1,350 average

### 📊 **Behavioral Patterns**
- **Purchase Seasonality**: 35% higher sales in Q4
- **Product Affinity**: Cross-sell opportunities identified
- **Channel Preference**: 62% prefer mobile, 38% web
- **Price Sensitivity**: 23% highly sensitive to discounts

## Business Recommendations
### 🎯 **Targeted Strategies**
- **Champions**: VIP program and exclusive previews
- **At Risk**: Personalized win-back campaigns
- **New Customers**: Onboarding sequence and education
- **Need Attention**: Re-engagement with special offers

### 📈 **Expected Impact**
- **Revenue Increase**: 15-25% through targeted campaigns
- **Customer Retention**: 30% improvement in at-risk segments
- **Marketing ROI**: 3.2x improvement vs mass campaigns
- **Customer Satisfaction**: Personalization improves NPS by 18 points

## Technical Methods
- **Clustering**: K-means, hierarchical clustering
- **Statistical Analysis**: Cohort analysis, survival curves
- **Visualization**: Customer journey mapping, heatmaps
- **Tools**: Python, pandas, scikit-learn, plotly
