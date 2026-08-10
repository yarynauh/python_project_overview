# E-commerce Sales Analytics Project

An end-to-end sales analysis project where I explored customer behavior, traffic sources, and revenue performance for an e-commerce store. 

The main goal was to clean the raw transactional data, test key business hypotheses using statistics, and turn the findings into an interactive Tableau dashboard for decision-making.

---

## What I Did in This Project

1. **Extracted and cleaned data** from Google BigQuery using SQL.
2. **Ran exploratory data analysis (EDA)** in Python to find patterns in revenue, categories, and device usage.
3. **Performed hypothesis testing** (Chi-Square, Mann-Whitney U, Z-tests) to validate whether observed differences were statistically significant.
4. **Built a single-page Tableau dashboard** with dynamic filters by date, continent, and traffic channel.

---

## Key Insights & Findings

* **Search is the main driver:** Organic (~35.8%) and Paid Search (~26.6%) generate over 60% of overall revenue. Social Search brings in surprisingly little (~7.9%).
* **Desktop converts better:** While mobile gets plenty of traffic, desktop users generate significantly more revenue and show higher completion rates.
* **Q4 spike:** Revenue stays steady through the first three quarters, then jumps sharply in November and December due to Black Friday and holiday promotions.

### Statistical Notes
* **No regional difference in devices:** A Chi-Square test showed that location doesn't really affect device choice ($p > 0.05$). The preference pattern is global.
* **Mobile users don't buy cheaper items:** The proportion of high-value purchases is equal on Mobile and Desktop ($p = 0.18$). The lower revenue on mobile comes from checkout friction/drop-offs, not lower average spend.

---

## Business Recommendations

1. **Double down on Search:** Shift marketing budget toward SEO and Google Ads, as search channels show the highest return.
2. **Fix Mobile Checkout:** Focus on improving the mobile buying experience to close the conversion gap with desktop.
3. **Prepare early for Q4:** Start scaling up ad campaigns in late October to fully capture the holiday shopping peak.

---

## Tech Stack
* **SQL (BigQuery):** Data extraction, aggregations, CTEs.
* **Python (Pandas, NumPy, Matplotlib, Seaborn):** Data cleaning, EDA, statistical testing.
* **Tableau Public:** Executive dashboard development.
* **Git:** Version control.

---

## Tableau Dashboard
* **Interactive Dashboard:** [Tableau Public](#) *(додай своє посилання)*
