# ☕ Coffee Shop Sales Analysis

Exploratory data analysis of a coffee shop chain operating across 
3 locations in New York City, covering 149,116 transactions over 
the first half of 2023.

This project demonstrates end-to-end data analysis skills: data loading, 
cleaning, transformation, visualization, and business insight generation 
using Python and pandas.

---

## 📊 Key Findings

| Metric | Result |
|---|---|
| Total Revenue | $698,812.33 |
| Total Transactions | 149,116 |
| Average Ticket | $4.69 |
| Period | Jan 2023 – Jun 2023 |
| Best Performing Store | Hell's Kitchen ($236,511.17) |
| Top Product | Barista Espresso ($91,406.20) |
| Top Category | Coffee ($269,952.45) |
| Peak Sales Hour | 10:00h |

---

## 💡 Business Insights

- **Coffee dominates revenue** — accounting for 38.6% of total sales, 
  making it the core product to protect and grow
- **Hell's Kitchen outperforms** other locations consistently — 
  its operational practices should be benchmarked across stores
- **Morning peak at 10am** — marketing campaigns and staffing should 
  be concentrated between 8am and 11am for maximum impact
- **Barista Espresso leads** all individual products — 
  upsell and bundle opportunities should center around this item

---

## 🛠️ Tech Stack

- **Python 3.13**
- **pandas** — data manipulation and aggregation
- **matplotlib / seaborn** — data visualization
- **Jupyter Notebook** — interactive analysis environment

---

## 📁 Project Structure

coffee-sales-analysis/
│
├── data/
│   ├── raw/              ← original dataset (Kaggle)
│   └── processed/        ← generated charts and cleaned data
│
├── notebooks/
│   └── 01_exploratory_analysis.ipynb
│
├── src/                  ← reusable scripts (coming soon)
└── README.md


---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/eduardolamarca/coffee-sales-analysis.git
cd coffee-sales-analysis
```

2. Install dependencies
```bash
pip install pandas matplotlib seaborn jupyter openpyxl
```

3. Launch Jupyter
```bash
jupyter notebook
```

4. Open `notebooks/01_exploratory_analysis.ipynb` and run all cells

---

## 📂 Data Source

[Coffee Shop Sales — Kaggle](https://www.kaggle.com/datasets/parasrupani/coffee-shop-sales)

---

*Project by [Eduardo Lamarca](https://www.linkedin.com/in/eduardo-lamarca-82099b211/) 
— Data Analyst open to opportunities in Europe 🇪🇺*