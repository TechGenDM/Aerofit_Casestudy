# 🏃 Aerofit Case Study — Customer Profiling & Product Intelligence

> **Exploratory Data Analysis | Customer Segmentation | Business Recommendations**

---

## 📌 Overview

This project is a comprehensive business case study for **Aerofit**, a leading fitness equipment brand. The goal is to investigate the characteristics of customers purchasing different treadmill models — **KP281**, **KP481**, and **KP781** — and build customer profiles to help the sales and marketing teams make better data-driven recommendations.

The analysis answers questions like:
- What kind of customer buys which treadmill?
- How do demographics (age, income, gender, fitness level) influence product choice?
- What are the conditional and marginal probabilities for each product?

---

## 📁 Repository Structure

```
Aerofit_Casestudy/
│
├── Aerofit_CaseStudy_UPDATED.ipynb   # Main analysis notebook
└── Aerofit_Intelligence_Report.pdf   # Final business intelligence report
```

---

## 🎯 Business Objective

Aerofit wants to identify the **target audience** for each treadmill product to improve:
- Product recommendations for new customers
- Marketing campaign targeting
- Inventory and sales strategy

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical analysis |
| Matplotlib / Seaborn | Data visualization |
| Jupyter Notebook | Interactive analysis |

---

## 📊 Analysis Walkthrough

### 1. Data Understanding
- Dataset contains customer purchase records with attributes: product purchased, age, gender, education, marital status, usage frequency, fitness self-rating, income, and miles run per week.

### 2. Exploratory Data Analysis (EDA)
- Univariate analysis of each feature (distributions, outlier detection)
- Bivariate analysis across product categories
- Countplots, boxplots, and heatmaps to uncover patterns

### 3. Customer Profiling
- Built distinct customer personas for KP281, KP481, and KP781
- Analyzed how income, age, fitness level, and gender correlate with product choice

### 4. Probability Analysis
- Marginal probabilities (e.g., P(Product = KP281))
- Conditional probabilities (e.g., P(Product = KP781 | Gender = Male))
- Cross-tabulation and pivot tables

### 5. Business Recommendations
- Data-driven suggestions for targeting each customer segment
- Presented in the `Aerofit_Intelligence_Report.pdf`

---

## 👤 Customer Profiles (Summary)

| Product | Typical Customer |
|---|---|
| **KP281** | Entry-level buyer; moderate income; occasional runner |
| **KP481** | Mid-range buyer; moderate-to-high fitness level; mixed gender |
| **KP781** | Premium buyer; high income; high fitness level; predominantly male |

---

## 📄 Intelligence Report

The `Aerofit_Intelligence_Report.pdf` contains a polished business report with visualizations, key findings, and actionable recommendations suitable for a stakeholder presentation.

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/TechGenDM/Aerofit_Casestudy.git
cd Aerofit_Casestudy

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook Aerofit_CaseStudy_UPDATED.ipynb
```

---

## 📬 Contact

**TechGenDM** — [GitHub Profile](https://github.com/TechGenDM)

---

*This project was completed as part of a data analytics/data science learning journey. Feel free to fork, star ⭐, or raise issues!*