# 📊 Customer Segmentation with RFM Analysis

## Project Overview
This project demonstrates a comprehensive RFM (Recency, Frequency, Monetary) analysis for customer segmentation using Python. The analysis helps identify different customer segments based on their purchasing behavior, allowing for targeted marketing strategies.

## Dataset Information
The analysis uses a customer transaction dataset with the following columns:
- CustomerID: Unique identifier for each customer
- OrderID: Unique identifier for each order
- PurchaseDate: Date of purchase (parsed as datetime)
- TransactionAmount: Monetary value of the transaction

# Analysis of RFM Value Segment Distribution Plot

## 📊 Plot Overview
The visualization titled "RFM Value Segment Distribution" shows how customers are distributed across three value segments: Low, Medium, and High.

![](newplot-2.png)

## 🔍 Key Observations

1. **Segment Distribution**:
   - The Medium value segment has the highest number of customers
   - The High value segment has the second highest count
   - The Low value segment has the fewest customers

2. **Business Implications**:
   - The distribution shows a healthy customer base with more customers in Medium and High value segments
   - The relatively smaller Low value segment suggests effective customer acquisition or retention strategies
   - The substantial High value segment indicates strong revenue potential from loyal customers

3. **Strategic Insights**:
   - The Medium segment represents the largest opportunity for growth through upselling and increased engagement
   - High value customers should be targeted with premium retention strategies
   - Low value customers might benefit from reactivation campaigns or improved onboarding


## Key Findings

1. **Customer Segmentation**: The analysis successfully segmented customers into distinct groups:
   - Champions: Best customers who buy recently, frequently, and spend the most
   - Potential loyalists: Recent customers with good frequency and monetary values
   - At risk Customers: Customers who used to purchase often but haven't recently
   - Can't Lose: Former Champions who haven't purchased recently
   - Lost: Least engaged customers

2. **Value Distribution**: The majority of customers fall into the Medium value segment, with a significant number of High value customers (Champions).

3. **Correlation Patterns**: In the Champions segment, frequency and monetary values show a strong positive correlation, indicating that customers who buy often also tend to spend more.

## Strategic Recommendations

1. **Champions Retention**: 
   - Implement loyalty programs to maintain engagement
   - Offer exclusive products or early access to new collections
   - Personalize communication based on their purchase history

2. **Potential Loyalists Development**:
   - Create targeted upsell campaigns
   - Offer incentives for repeat purchases
   - Gather feedback to understand their needs

3. **At-Risk Customers Reactivation**:
   - Develop win-back campaigns with special offers
   - Send personalized emails reminding them of products they might like
   - Conduct surveys to understand why they stopped purchasing

4. **Can't Lose Customers Recovery**:
   - Implement aggressive reactivation campaigns
   - Offer significant discounts or value-added services
   - Personalize communication to show they're valued

5. **Low-Value Customers**:
   - Focus on cost-effective marketing strategies
   - Nurture with educational content about product benefits
   - Test different engagement strategies to identify what works

## Technical Implementation Notes

- Used pandas for data manipulation and RFM calculation
- Utilized Plotly for interactive visualizations
- Implemented binning techniques for RFM scoring
- Applied correlation analysis to understand relationships between RFM dimensions

This RFM analysis provides a powerful framework for understanding customer behavior and implementing targeted marketing strategies to improve customer retention and lifetime value.
