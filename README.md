# BasketLens: E-Commerce Customer Analytics & Market Basket Insights

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)

An end-to-end data analytics and market basket insights solution designed for e-commerce platforms. **BasketLens** processes raw transactional data, uncovers customer purchasing behavior, identifies product association rules, and visualizes business KPIs through interactive dashboards.

---

## 📊 Key Highlights & Features

- **Data Cleaning & Pipeline Engine:** Automated preprocessing pipelines to handle missing data, transform transaction timestamps, and clean user behavioral logs.
- **Market Basket Analysis (Association Rules):** Implements Apriori/FP-Growth algorithms to discover product association rules (Support, Confidence, Lift) for cross-selling strategies.
- **Customer Segmentation:** Analyzes RFM (Recency, Frequency, Monetary) metrics to segment shoppers into high-value, active, and at-risk categories.
- **Power BI Business Dashboards:** Interactive dashboard templates capturing Revenue Trends, Top Associated Products, Average Order Value (AOV), and Regional Sales performance.

---

## 🏗️ Project Architecture

```
Raw Transactional Data ──► Data Cleaning & Normalization (Pandas/NumPy)
                                 │
                                 ▼
                     Market Basket Analysis (Apriori/Lift)
                                 │
                                 ▼
                  Power BI Analytics & Executive Dashboard
```

---

## 📁 Repository Structure

```
basketlens/
├── BasketLens_Project/       # Core project notebooks and pipeline code
├── cleaned_data/              # Preprocessed dataset schema (sample output)
├── notebooks/                 # Exploratory data analysis & association rule notebooks
├── powerbi/                   # Power BI report files (.pbix templates)
├── report/                    # Project summary documents & findings
├── screenshots/               # Dashboard preview images & visualizations
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
```

*Note: Raw transactional customer datasets are excluded from the public showcase repository for privacy compliance.*

---

## 🛠️ Installation & Setup

```bash
git clone https://github.com/tzmughal/basketlens.git
cd basketlens
pip install -r requirements.txt
```

---

## 👤 Author
- **GitHub:** [@tzmughal](https://github.com/tzmughal)
