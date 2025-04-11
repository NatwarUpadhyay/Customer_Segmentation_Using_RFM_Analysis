# Customer_Segmentation_Using_RFM_Analysis

![RFM Segments](https://img.shields.io/badge/Analysis-RFM_Segmentation-blue) 
![License](https://img.shields.io/badge/License-MIT-green)

A data-driven approach to segment customers based on **Recency**, **Frequency**, and **Monetary Value (RFM)**. This project identifies distinct customer groups and suggests targeted marketing strategies to improve retention and revenue.

---

## 📊 Project Overview
This analysis processes purchase history data to classify customers into actionable segments such as **Champions**, **Loyal Customers**, **At Risk**, and others. Key steps include:
1. **Data Preparation**: Clean and explore transactional data.
2. **RFM Calculation**: Compute metrics for customer behavior.
3. **Segmentation**: Assign customers to strategic groups using quantile-based scoring.
4. **Actionable Insights**: Recommend tailored marketing strategies for high-impact segments.

---



       Install dependencies:
    bash
    Copy

    pip install pandas numpy matplotlib seaborn

🛠️ Usage
Key Steps

    Load Data: Import purchase records and preprocess dates.

    Calculate RFM Metrics:

        Recency: Days since last purchase.

        Frequency: Total transactions per customer.

        Monetary Value: Average spending per customer.

    Segment Customers: Assign scores (1-3) for each RFM dimension and map to segments (e.g., "Champions").

    Visualize Results: Plot segment distributions and analyze trends.

Output Highlights

    Segment Distribution:
    Segment	Customers Count
    Champions	1,095
    Loyal Customers	912
    Promising	591
    At Risk	613
    Hibernating	480
    About to Sleep	405
    Cannot Lose	319
    Need Attention	260
    Potential Loyalists	244

    Top Segments: Champions (high spenders) and Loyal Customers (consistent buyers).

    Marketing Actions:

        🏆 Champions: Offer exclusives (e.g., early access, VIP discounts).

        💎 Loyal Customers: Personalize recommendations and loyalty rewards.

📈 Results

    Visualization: Histograms for RFM distributions and bar plots for segment sizes.

    Key Insights:

        Champions contribute significantly to revenue (high monetary value).

        At Risk and Hibernating segments require re-engagement campaigns.

📜 License

Distributed under the MIT License. See LICENSE for details.
🙌 Acknowledgments

    RFM methodology inspired by marketing analytics best practices.

    Dataset: Transactional purchase records (purchases.txt).



This README focuses on **clarity** and **actionable insights**, avoiding code snippets while emphasizing the workflow, results, and strategic recommendations. The use of badges, tables, and emojis enhances readability and engagement.
