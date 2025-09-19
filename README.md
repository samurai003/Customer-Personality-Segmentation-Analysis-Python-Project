# Customer Personality & Segmentation — Python

This repository contains an end‑to‑end workflow for **customer personality & purchasing‑behavior segmentation**. It turns raw demographic, lifestyle, and spend data into **actionable segments** for targeted marketing, retention, and merchandising.

## 🔍 Problem & Objectives
- Understand distinct customer groups from demographics, behavior, and spend
- Personalize campaigns and improve retention (high‑value cohorts)
- Inform inventory, pricing, and store/web layout decisions

## 📦 Data (example schema)
- **Customer Info:** ID, Year_Birth, Education, Marital_Status, Income, Kidhome, Teenhome, Dt_Customer, Recency, Complain  
- **Spend (2y):** MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds  
- **Purchases/Campaigns:** NumDealsPurchases, AcceptedCmp1–5, Response  
- **Shopping Behavior:** NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth

> Place the dataset in `data/` and update paths in the notebook.

## 🧠 Methods
- Data cleaning (missing values, outliers), encoding & scaling
- **EDA**: spend distribution, channel mix, recency, tenure
- **Feature engineering**: totals, ratios, RFM‑style signals
- **Clustering**: K‑Means ± silhouette/Elbow; optional Hierarchical/DBSCAN
- **Profiling**: name/describe segments; link to business levers

## 📈 Results (template)
- 4–6 segments with clear business narratives
- Examples: “High‑income Wine Loyalists”, “Deal‑Seeking Omni‑Channel Families”
- Recommended actions per segment

## 🚀 Quickstart
```bash
# 1) Create and activate env
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 2) Launch notebook
jupyter lab  # or: jupyter notebook
```

Open: **`Customer Personality Segmentation Project.ipynb`**
