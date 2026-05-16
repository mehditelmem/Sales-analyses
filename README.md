# 📊 Sales Analysis — Python & Pandas

> Exploratory data analysis of a physical products sales dataset to uncover actionable business insights using Python.

---

## 🎯 Business Questions Answered

This project tackles 5 real-world business questions:

1. **What was the best month for sales?** — And how much revenue was generated?
2. **Which US city had the highest number of sales?** — Geographic performance analysis
3. **What is the best time to display advertisements?** — To maximize purchase likelihood
4. **What products are most often sold together?** — Market basket / cross-sell analysis
5. **What product sold the most?** — And why? (price vs. volume analysis)

---

## 📁 Dataset

- **Type:** Physical products sales data
- **Format:** CSV files (monthly sales data merged into one master dataset)
- **Source:** Kaggle
- **Size:** 1717 rows

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| Python 3 | Core language |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Data visualization |
| Jupyter Notebook | Analysis environment |

---

## 🔍 Methodology

### 1. Data Preparation
- Merged 12 monthly CSV files into a single DataFrame
- Handled missing values and NaN rows
- Parsed and converted data types (dates, numeric values)
- Added derived columns: Month, City, Hour, Sales Amount

### 2. Exploratory Analysis
Each business question was addressed with dedicated analysis and visualization.

---

## 📈 Key Findings

### 🏆 Best Month for Sales
> December was the best month with over $4,000,000 in revenue — driven by holiday season demand.

---

### 🌆 Best City for Sales
> San Francisco had the highest sales volume with over $8,000,000 in total revenue.
---

### ⏰ Best Time for Advertisements
> Peak purchase activity occurs around 19:00 (7 PM) — the optimal window to display ads and maximize conversion.
---

### 🛒 Products Most Often Sold Together
> iPhone + Lightning Charging Cable was the most frequent product bundle, appearing together in 1,005 orders — a strong cross-sell opportunity.
---

### 📦 Best Selling Product
> AAA Batteries (4-pack) was the top-selling product by volume. This is likely due to its low price point and high consumption rate — customers need to replace batteries frequently for multiple devices.
---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/mehditelmem/Sales-analyses.git
cd Sales-analyses

# Install dependencies
pip install pandas matplotlib jupyter

# Launch notebook
jupyter notebook analycess.ipynb
```

---

## 👤 Author

**Mehdi Telmem** — Data Analyst Junior  
📧 mitelmem@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mehdi-telmem) | [GitHub](https://github.com/mehditelmem)
