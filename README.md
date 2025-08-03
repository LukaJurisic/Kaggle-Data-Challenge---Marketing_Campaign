# 🧠 Customer Segmentation — Kaggle Marketing Campaign

A full-stack data science project that applies unsupervised learning to uncover distinct customer personas based on real marketing data. The project demonstrates practical clustering, interpretability, and visual storytelling.

> 📁 This project is part of my personal portfolio and designed to showcase real-world analytics workflows with a business impact lens.

---

## 🧾 Dataset

- **Source**: [Kaggle Marketing Campaign Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- **Size**: ~2,200 rows × 29 columns
- **Context**: Consumer demographic + transaction data from a marketing campaign

---

## 💡 Objective

Segment customers based on purchasing behavior, lifestyle, and demographics to inform persona-based targeting strategies.

---

## 🧪 Techniques Used

| Step                         | Tools / Methods                              |
|------------------------------|-----------------------------------------------|
| Data Cleaning                | Pandas, NumPy                                 |
| Feature Engineering          | Spending ratios, age groups, total spend      |
| Dimensionality Reduction     | PCA                                           |
| Clustering                   | K-Means (optimal `k` via elbow + silhouette)  |
| Cluster Interpretation       | SHAP (SHapley Additive exPlanations)         |
| Visualization                | Matplotlib, Seaborn                           |

---

## 📊 Key Visuals

| Insight Area                    | Example Output File                            |
|----------------------------------|------------------------------------------------|
| Age vs Income Distribution      | `age_income_distribution.png`                 |
| Explained Variance by PCA       | `pca_variance.png`                            |
| Final Clusters (PCA space)      | `kmeans_clusters.png`                         |
| SHAP Summary per Cluster        | `shap_summary.png`                            |
| Final Personas / Recommendations| `persona_cards.png`                           |

_All visuals are exported in `.png` format for clean web display._

---

## 🎯 Final Personas

| Cluster | Key Traits | Strategic Recommendation |
|--------|-------------|---------------------------|
| 0 | Older, low spend, retired | Ignore or deprioritize |
| 1 | Mid-age, balanced spending | Test new bundles |
| 2 | High-income, high spend | VIP Loyalty Program |
| 3 | Younger, luxury-focused | Upsell premium tiers |

---

## 🖥️ Portfolio Integration

This project is fully integrated into my [personal website](https://yourwebsite.com) built with React + Tailwind. Explore the interactive version [here](https://yourwebsite.com/customer-segmentation).

---

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/LukaJurisic/Kaggle-Data-Challenge---Marketing_Campaign.git
   cd Kaggle-Data-Challenge---Marketing_Campaign
