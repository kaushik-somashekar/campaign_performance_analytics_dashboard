# Campaign Performance Analytics Dashboard

## Project Overview

This project is a **Campaign Performance Analytics Dashboard** using digital marketing data across paid, owned, affiliate, and organic channels.


---

## Business Problem

Marketing teams need a single view of campaign performance to understand:

- Which channels drive revenue?
- Which campaigns deliver the strongest ROAS?
- Where is CPA too high?
- Which campaigns should receive more or less budget?
- How do device and region affect performance?

The key business question is:

> How can we monitor marketing campaign performance and make better budget allocation decisions?

---

## Dataset

The dataset is synthetic but designed to reflect realistic campaign analytics data.

### Files

```text
data/campaign_daily_performance.csv
data/channel_weekly_budget.csv
data/data_dictionary.csv
```

### Dataset Size

- 90 days of daily campaign data
- 8 marketing channels
- 29 campaigns
- Region and device dimensions
- Spend, impressions, clicks, conversions, revenue, ROAS, CPA, CTR, CPC, CVR

---

## Channels Included

- Google Ads
- Meta Ads
- Email
- Affiliate
- Organic Search
- Display
- TikTok Ads
- Bing Ads

---

## KPIs Included

```text
Spend
Revenue
ROAS
CPA
CTR
CPC
Conversion Rate
Impressions
Clicks
Conversions
New Customers
Assisted Conversions
AOV
```

---

## Folder Structure

```text
campaign_performance_analytics_dashboard/
│
├── data/
│   ├── campaign_daily_performance.csv
│   ├── channel_weekly_budget.csv
│   └── data_dictionary.csv
│
├── notebooks/
│   └── campaign_performance_analytics_dashboard.ipynb
│
├── reports/
│   ├── dashboard_kpi_cards.csv
│   ├── channel_performance_summary.csv
│   ├── campaign_performance_summary.csv
│   ├── daily_trend_summary.csv
│   ├── device_channel_summary.csv
│   ├── business_recommendations.csv
│   └── figures/
│       ├── revenue_by_channel.png
│       ├── roas_by_channel.png
│       ├── daily_spend_revenue_trend.png
│       ├── top_campaigns_by_roas.png
│       └── conversion_rate_by_device.png
│
├── dashboard_assets/
│   └── dashboard_blueprint.md
│
├── docs/
│   └── project_summary.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Dashboard Pages

### 1. Executive Overview

KPI cards for:

- Spend
- Revenue
- ROAS
- CPA
- Conversion Rate
- CTR
- Conversions
- New Customers

### 2. Channel Performance

Compares channels by spend, revenue, ROAS, CPA, and conversion rate.

### 3. Campaign Deep Dive

Campaign-level table with filters for channel, campaign type, region, and device.

### 4. Trend Analysis

Daily spend, revenue, conversions, and ROAS trends.

### 5. Device and Region Analysis

Performance breakdown by device and market.

---

## Key Outputs

| Output | Description |
|---|---|
| `dashboard_kpi_cards.csv` | Executive KPI card values |
| `channel_performance_summary.csv` | Channel-level marketing performance |
| `campaign_performance_summary.csv` | Campaign-level performance summary |
| `daily_trend_summary.csv` | Daily performance trend |
| `device_channel_summary.csv` | Device and channel performance |
| `business_recommendations.csv` | Business recommendations |
| `revenue_by_channel.png` | Revenue by channel visual |
| `roas_by_channel.png` | ROAS by channel visual |
| `daily_spend_revenue_trend.png` | Daily trend visual |
| `top_campaigns_by_roas.png` | Top campaigns by ROAS |
| `conversion_rate_by_device.png` | CVR by device |

---

## Business Recommendations

### Budget Allocation

Shift incremental budget toward high-ROAS and low-CPA campaigns while protecting upper-funnel channels that contribute assisted conversions.

### Email and Retention

Scale basket recovery, loyalty, and lifecycle campaigns because owned channels usually show strong efficiency.

### Paid Search

Separate brand and non-brand performance. Monitor shopping campaign ROAS and non-brand CPA.

### Paid Social

Evaluate using assisted conversions and incrementality instead of last-click ROAS only.

### Display

Reduce broad prospecting waste and focus on retargeting, frequency caps, and high-intent audiences.

### Device Optimization

Improve mobile landing page speed, checkout flow, and message relevance if mobile CVR lags behind desktop.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Campaign Analytics
- Marketing Analytics
- Dashboard Design
- ROAS Analysis
- CPA Analysis
- Performance Marketing

---

## Author

Kaushik Somashekar  
Digital Analyst | Product Analyst | Data Analyst | Aspiring Data Scientist
