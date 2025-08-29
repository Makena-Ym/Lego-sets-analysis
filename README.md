# Lego-sets-analysis
Analyze LEGO sets, themes, and colors using Python and pandas. Discover trends in set releases, theme popularity, and set complexity over time with real data and visualizations. Gain insights into LEGO’s growth and product strategy through data analysis techniques.

## 📊 Project Overview

This notebook walks through a complete data analysis workflow:
- **Data Loading & Exploration:** Import and inspect LEGO datasets (`colors.csv`, `sets.csv`, `themes.csv`).
- **Data Cleaning & Aggregation:** Group and summarize data to reveal patterns.
- **Visualization:** Use Matplotlib to create line charts, scatter plots, and dual-axis plots.
- **Advanced Analysis:** Merge datasets to answer complex questions about themes and set popularity.

---

## 🗂️ Datasets Used

- **colors.csv:** Contains all LEGO brick colors, including transparency info.
- **sets.csv:** Details every LEGO set, including year, theme, and number of parts.
- **themes.csv:** Lists all LEGO themes and their IDs.

All datasets are sourced from [Rebrickable](https://rebrickable.com/downloads/).

---

## 📈 Key Insights & Patterns

### 1. **LEGO Colors**
- There are dozens of unique LEGO colors, including both opaque and transparent bricks.
- Transparent colors are less common, but add variety and realism to sets.
- Data analysts can use `.nunique()` and `.groupby()` to quickly summarize color diversity and transparency.

### 2. **Set Releases Over Time**
- The number of LEGO sets released each year has grown dramatically, especially since the 1990s.
- Early years (1949–1950s) had only a handful of sets; recent years see hundreds annually.
- Line charts reveal clear periods of expansion, often coinciding with new themes or licensing deals.
- Analysts should look for spikes and dips to understand business cycles and product launches.

### 3. **Themes & Licensing**
- LEGO themes range from original (e.g., City, Ninjago) to licensed (e.g., Star Wars, Harry Potter).
- The most prolific themes have the largest number of sets, with licensed themes often dominating recent years.
- Merging set and theme data shows which themes are most popular and how their set counts compare.
- Data analysts can use `.value_counts()` and DataFrame merging to answer questions about theme popularity.

### 4. **Set Complexity**
- The average number of parts per set has increased over time, indicating more complex and detailed builds.
- Scatter plots show a clear upward trend in set size, especially for flagship sets.
- This pattern suggests LEGO’s strategy to appeal to older builders and collectors.

### 5. **Dual-Axis Visualization**
- Using two y-axes, the notebook compares the growth in the number of sets and themes per year.
- This reveals how LEGO’s strategy shifted to offer more variety and cater to different interests.
- Data analysts should use dual-axis plots to compare related metrics over time.

### 6. **Data Merging & Advanced Queries**
- By merging `sets.csv` and `themes.csv`, the notebook identifies the most popular themes and their set counts.
- Example: Star Wars has multiple theme IDs due to sub-themes, and merging helps analyze all related sets.
- This technique is essential for answering business questions that span multiple tables.

---

## 🖼️ Example Visualizations

- **Line Chart:** Number of sets released per year.
- **Line Chart:** Number of themes introduced per year.
- **Scatter Plot:** Average number of parts per set over time.
- **Dual-Axis Plot:** Sets vs. themes released per year.

---

## 📁 File Structure

```
lego-data-analysis/
│
├── final lego analysis.ipynb   # Main Jupyter notebook
├── colors.csv                  # LEGO colors data
├── sets.csv                    # LEGO sets data
├── themes.csv                  # LEGO themes data
└── README.md                   # This file
```

---

## 💡 Data Analyst Tips

- **Explore Relationships:** Use `.groupby()`, `.agg()`, and merging to uncover hidden patterns.
- **Visualize Trends:** Always plot your findings to spot trends and anomalies.
- **Check Data Quality:** Inspect for missing values, duplicates, and outliers.
- **Ask Business Questions:** Use the data to answer questions relevant to LEGO’s strategy, product development, and customer interests.
- **Document Insights:** Annotate your notebook with markdown cells explaining each step and insight.

---

## 🤝 Contributing

Contributions are welcome!  
- Fork the repo
- Create a new branch
- Submit a pull request

---

## 📄 License

This project is for educational purposes and uses public datasets.  
See [Rebrickable’s Terms of Use](https://rebrickable.com/downloads/) for dataset licensing.

---

## 🙋‍♂️ Contact

For questions or feedback, open an issue or reach out via [GitHub](https://github.com/Makena-Ym).

---

Happy building and analyzing! 🧱📊
Makena Gatere
