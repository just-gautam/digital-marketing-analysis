# 📊 Digital Marketing Performance Analysis

**Author:** Gautam Bhardwaj

## 🛠 Tools Used
Python · SQLite · Pandas · Matplotlib

## 📂 Dataset
Synthetic Digital Marketing Performance Dataset (30,000 rows)
Platforms: Meta, Google Search, TikTok, Snapchat, LinkedIn, Google Display

📄 See [README_DATASET.md](README_DATASET.md) for full data generation notes and caveats.

## 🔍 Analysis Performed
1. Revenue by Platform
2. CTR by Placement
3. Daily CPM Trends
4. Revenue by Country
5. Monthly Revenue Trend
6. Platform ROI Comparison
7. Funnel Stage Conversion Rate
8. Seasonal Performance

## 💡 Key Insights
- Google Search generates 6x more revenue than Meta ($10.3M vs $1.6M)
- KSA is #1 market with 61,641 conversions and $2.76M revenue
- Search placement has highest CTR (566%) among all placements
- Only Google Search shows positive ROI (+284%)
- Conversion funnel converts 84x better than Awareness stage

## 🚀 How to Run
pip install pandas matplotlib
Open Digital_Marketing_Analysis.ipynb in VS Code or Jupyter

## 📊 Looker Studio Dashboard

Live, filterable dashboard built on top of the cleaned dataset.

🔗 **[View Live Dashboard](https://datastudio.google.com/s/uab391qgCRU)**
📄 [Download PDF snapshot](assets/Digital_Marketing_Performance_Dashboard.pdf)

**Filters:** Platform, Placement, Country, Date range

**KPI Cards:** Total Revenue · Avg CPM · ROI

**Charts:**
- Revenue trend by platform (time series)
- Platform (publisher) comparison — Google Search leads with ~$10.3M
- Placement (format) breakdown — Stories and In-Feed drive the largest share of impressions
