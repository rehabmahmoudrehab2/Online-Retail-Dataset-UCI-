:

🛒 Customer Segmentation Using RFM Analysis

Dataset: Online Retail Dataset (UCI Machine Learning Repository)

Goal: Segment customers based on purchasing behavior using the RFM model:

Recency (R): How recently a customer made a purchase

Frequency (F): How often they purchased

Monetary (M): How much they spent

🔍 Steps Performed

Cleaned and prepared transactional data (removed duplicates, handled missing values).

Calculated RFM metrics for each customer.

Assigned RFM scores and categorized customers into behavior-based segments.

Visualized insights using heatmaps and bar charts.

📊 Key Insights
Chart 1: RFM Heatmap

Shows average values of Recency, Frequency, and Monetary for each customer segment.

| Segment                 | Recency | Frequency | Monetary |
| ----------------------- | ------- | --------- | -------- |
| **Champions**           | 19.27   | 17.12     | 9354.32  |
| **Loyal Customers**     | 73.16   | 5.95      | 2300.81  |
| **Potential Loyalists** | 25.85   | 2.17      | 1198.29  |
| **Promising**           | 80.51   | 1.00      | 389.87   |
| **At Risk**             | 370.74  | 6.18      | 2882.78  |
| **Need Attention**      | 250.99  | 2.34      | 606.16   |
| **New Customers**       | 10.30   | 1.00      | 356.26   |
| **Lost**                | 483.28  | 1.13      | 238.80   |
| **Others**              | 282.15  | 2.27      | 790.60   |


💡 Insight:

Champions purchase often, recently, and spend the most — your top priority for retention.

Lost customers have not purchased in a long time and spend the least — target them with reactivation offers.

Potential Loyalists and Promising segments are growing customers — nurture them with engagement campaigns.

Chart 2: Customer Segment Distribution

Shows the number of customers per segment.

S| Segment                 | Approx. Count |
| ----------------------- | ------------- |
| **Champions**           | ~1250         |
| **Lost**                | ~1150         |
| **Loyal Customers**     | ~1100         |
| **Need Attention**      | ~580          |
| **Others**              | ~550          |
| **At Risk**             | ~500          |
| **Potential Loyalists** | ~320          |
| **Promising**           | ~300          |
| **New Customers**       | ~80           |

💡 Insight:

Champions are the largest and most valuable group.

Lost and Loyal Customers also represent major portions — ideal for retention and recovery strategies.

🧭 Recommended Actions
Segment	Suggested Strategy
Champions	Reward loyalty with exclusive offers or early access.
Loyal Customers	Offer membership perks or referral programs.
Potential Loyalists	Send personalized product recommendations.
Promising	Encourage repeat purchases with discounts.
At Risk	Reconnect through win-back emails.
Need Attention	Offer reminders or small incentives.
Lost	Use re-engagement campaigns or surveys.
New Customers	Welcome with onboarding and discounts.
🧰 Tools & Libraries

Python

Pandas, NumPy

Seaborn, Matplotlib (or Excel for visualization)
