# 🇯🇵 Japan Birth Statistics Analysis (1899–2023)

Exploratory data analysis of 124 years of Japan's birth trends — uncovering the story behind one of the world's most significant demographic crises.

---

##  Dataset
- **Source:** Japan Vital Statistics
- **Range:** 1899 – 2023 (122 rows × 7 columns)
- **Features:** Total births, male/female births, crude birth rate, sex ratio, total fertility rate

---

##  What's Inside

| Section | Description |
|---|---|
| Data Cleaning | Identifying and handling missing values |
| NumPy Analysis | Mean, median, std, percentiles, correlation, decade averages |
| Pandas Feature Engineering | YoY change, rolling average, era labeling, groupby |
| Matplotlib Visualizations | 5 professional charts |

---

##  Visualizations

- Total Births Over Time + 10-Year Rolling Average
- Crude Birth Rate vs Total Fertility Rate
- Male vs Female Births (Stacked Area)
- Average Births by Historical Era
- Year-over-Year % Change

---

##  Tools
![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.24-green)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange)

---

##  Run Locally
```bash
git clone https://github.com/suzzzel5/Japan-Birth-Statistics-1899-2023-.git
cd japan-birth-analysis
pip install -r requirements.txt
jupyter notebook japan_birth_analysis.ipynb
```

---

##  Key Findings

- Japan's births peaked at ~2.7M in the early 1950s post-war baby boom
- The Total Fertility Rate dropped below replacement level (2.1) in the mid-1970s and never recovered
- 2023 recorded a historic low of just 727,288 births
- Strong negative correlation between year and total births confirms a long-term demographic decline