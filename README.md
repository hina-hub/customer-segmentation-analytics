# 🎯 Customer Segmentation & Market Basket Analytics

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

An end-to-end data science pipeline that analyzes customer personality traits, purchasing patterns, and campaign responses to segment customers and discover association rules for targeted marketing strategies.

---

## 📌 Project Overview

Understanding customer behavior is essential for optimizing marketing campaigns and maximizing ROI. This project explores customer demographics, spending habits, and promotional response rates using **Gaussian Mixture Models (GMM)** for clustering and **Apriori Algorithm** for association rule mining.

### Key Objectives
* **Data Preprocessing & Feature Engineering:** Clean missing values, engineer custom metrics (e.g., `MntTotal`, `AverageCheck`, `Family_size`), and handle outliers.
* **Customer Clustering:** Apply Gaussian Mixture Models to partition customers into actionable personas.
* **Market Basket Analysis:** Utilize frequent pattern mining (Apriori & Association Rules) to identify co-purchasing habits.
* **Data Visualization:** Build interactive and static visualizations using `Seaborn`, `Matplotlib`, and `Plotly`.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning & Stats:** `scikit-learn` (StandardScaler, GaussianMixture, Metrics)
* **Market Basket Analysis:** `mlxtend` (Apriori, Association Rules)
* **Data Visualization:** `seaborn`, `matplotlib`, `plotly`

---

## 📊 Methodology & Workflow

1. **Exploratory Data Analysis (EDA):**
   * Identified distributions and outliers across income, spending, and purchasing channels.
   * Handled missing values using median imputation.
2. **Feature Engineering:**
   * Derived metrics like `Days_is_client`, `TotalAcceptedCmp`, and simplified marital statuses into binary relationship categories.
3. **Segmentation (Clustering):**
   * Standardized features and fitted a **Gaussian Mixture Model** to discover latent customer segments.
4. **Association Rule Mining:**
   * Evaluated itemset frequencies using `apriori` and derived support, confidence, and lift metrics.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed, then clone the repository:

```bash
git clone [https://github.com/hina-hub/datasscience-project.git](https://github.com/hina-hub/datasscience-project.git)
cd datasscience-project
Installation
Install the required dependencies:

Bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn mlxtend
Running the Notebook
Launch Jupyter Notebook to view and run the analysis:

Bash
jupyter notebook ids.ipynb
💡 Key Insights & Takeaways
High-income customers show significantly higher response rates to direct marketing campaigns.

Association rules reveal strong co-purchasing patterns between wine and meat products, suggesting optimal bundle strategies.

Web vs. Store purchasing preferences differ distinctly across age and family size demographics.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
