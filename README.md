# Marketing Funnel & Conversion Performance Analysis

Marketing funnel and conversion analysis built for a Data Science & Analytics internship task. The project analyzes 500,000 e-commerce behavioral events to understand how users move through the funnel from product views to purchases, identify drop-off points, and provide actionable recommendations to improve conversion rates.

## Objective

Analyze marketing funnel data the way a real growth analyst would, answering:
- Where are users dropping off in the funnel?
- Which product categories convert best?
- How do customers actually purchase — via cart or directly?
- How can conversion rates be improved?

## Dataset

**E-Commerce User Behavior Dataset** (Kaggle) — 500,000 behavioral events from October 2019, with 9 fields: event_time, event_type (view/cart/purchase), product_id, category_id, category_code, brand, price, user_id, user_session.
Source: https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

## Tools Used

Python 3 (Jupyter Notebook) — pandas, matplotlib, seaborn, plotly, kaleido.

## Repository Structure

```
├── README.md
├── Marketing_Funnel_Analysis.ipynb
├── Marketing_Funnel_Analysis_Report.pdf
└── screenshots/
    ├── funnel_chart.png
    ├── category_conversion.png
    ├── hourly_pattern.png
    ├── top_brands.png
    └── purchase_path_comparison.png
```

## Key Findings

| KPI | Value |
|-----|-------|
| Total Users | 89,124 |
| Users who Viewed | 89,108 (100%) |
| Users who Added to Cart | 4,441 (5%) |
| Users who Purchased | 7,362 (8.26%) |
| Overall Conversion Rate | 8.26% |
| Drop-off Rate | 91.74% |
| Total Revenue | $3,115,564 |
| Avg Order Value | $319.28 |

**62.6% of buyers purchase directly without using the cart.**
Top category: Electronics (3.18% conversion). Top brands: Samsung, Apple.
Peak traffic: Hours 7-9 UTC.

## Recommendations

1. Optimize direct purchase experience — most buyers skip the cart
2. Re-engage 81,746 browse-only users with retargeting campaigns
3. Double down on Electronics — highest traffic + conversion
4. Deploy promotions during peak hours 7-9 UTC
5. Use cart incentives (bundles, free shipping) to lift avg order value
6. Add comparison tools and financing options for Appliances and Computers

## Author

Naredla Poojitha — Data Science & Analytics Intern
