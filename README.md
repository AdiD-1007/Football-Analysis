# ⚽ FIFA 21 Player Data - Exploratory Data Analysis (EDA)

This is a beginner-friendly yet insightful **data analysis project** based on the **FIFA 21 player dataset** from Kaggle. The goal of this project is to explore the dataset, analyze current and future player performance, and visualize meaningful football insights using Python.

---

## 📌 About the Dataset

- **Dataset Name:** `players_21.csv`  
- **Source:** [Kaggle - FIFA 21 Complete Player Dataset](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset)  
- The dataset includes data on over **18,000 footballers**, including:
  - Age, nationality, height, weight
  - Club and league information
  - Skill stats, overall ratings, and potential
  - Wages, values, and player positions

---

## 🔍 Objectives of the Project

- Analyze player distribution by **age**, **nationality**, and **positions**
- Identify **top-rated players** and **clubs** based on overall and potential
- Compare current vs. upcoming **top clubs and leagues**
- Discover clubs with most **future superstars**
- Export all visualizations into a clean **PDF report**

---

## 📊 Key Visualizations Included

- Top 10 **players** by overall rating
- Age distribution of all players
- Most common player positions
- Wage distribution of top 100 players
- Top 10 countries by number of players
- Top 10 clubs by:
  - Combined overall rating of best 11 players
  - Number of future superstars (potential ≥ 75 & gap ≥ 5)
- Top 10 **leagues** based on:
  - Current average overall rating
  - Future average potential rating

📄 All plots are exported into a single PDF file: **`fifa21_report.pdf`**

---

## 🛠 Tools & Libraries Used

- **Python** (Pandas, NumPy)
- **Seaborn** and **Matplotlib** for static visualizations
- `matplotlib.backends.backend_pdf` for exporting to PDF
- **VS Code** or **Jupyter Notebook** for development

---

## 📁 How to Run

1. Download the dataset: [`players_21.csv`](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset)
2. Place it in the same folder as the script.
3. Run the analysis script:

```bash
python fifa21analysis.py
````

4. Check the output PDF: `fifa21_report.pdf`

---

Feel free to fork, clone, or build on this for deeper insights like team comparison, skill attribute analysis, or predictive modeling!
