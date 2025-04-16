# ⚽ Tottenham Hotspur 2024/25 Attacking Player Analysis

### Matchweek 1–32 (All Competitions) | Last Updated: April 15th, 2025  
**Author:** Ezekiel Loty

---

## 📊 Overview

This project offers a comprehensive performance analysis of **Tottenham Hotspur's attacking players** during the 2024/25 season across all competitions up to Matchweek 32.

Using real data scraped from FBref, this report highlights key metrics such as:

- Goals, Assists, xG, xA (per 90)
- Shot efficiency and conversion
- Creative output (Key Passes, Progressive Passes, Passes into Penalty Area)
- Over/underperformance vs expected goals
- Player radar comparisons and custom **Efficiency Index**

Interactive and static visualizations provide an intuitive understanding of player output throughout the season.

---

## 📁 Dataset

- Source: [FBref.com](https://fbref.com)
- File: `csv-files/player.csv`
- Columns include: `Player`, `Pos`, `Age`, `90s`, `Gls`, `Ast`, `xG`, `xA`, `Sh`, `KP`, `Cmp%`, `PrgP`, `PrgC`, etc.

---

## 📌 Key Features

- 🎯 **Goal Contributions per 90**: Goals and Assists normalized per 90 minutes.
- 📉 **xG vs Actual Goals**: Insights into finishing efficiency.
- 📊 **Shot Conversion vs Frequency**: Volume vs accuracy trade-offs.
- 🧠 **Creative Output Heatmap**: Visualizes KP, xA, PPA, etc.
- 🌀 **Radar Chart**: Compare key attackers across multiple standardized metrics.
- ⚡ **Efficiency Index**: Custom formula combining attacking metrics into a performance score.
- 🌐 **Interactive Plotly Dashboard**: Summary of performance metrics in an intuitive layout.

---

## 🖼️ Visualizations

### 1. Goal Contributions Per 90  
Bar chart comparing goals and assists per 90 minutes for each attacker.

### 2. Expected Goals vs Actual Goals  
Side-by-side bar chart showcasing xG vs real goals to highlight finishing ability.

### 3. Radar Chart  
Polar plot comparing top 5 attacking players based on standardized metrics.

### 4. Creative Heatmap  
Visualizes key pass and progressive metrics across most creative attackers.

### 5. Efficiency Index  
Ranks players by a weighted formula emphasizing goals, assists, shot performance, and creativity.

### 6. Interactive Dashboard  
Built with Plotly – explore goals, assists, conversion rates, progressive actions, and more.

---

## 📌 Efficiency Index Formula

To create a single score for attacker impact:

```
Efficiency Index =
(Gls_per90 × 3) +
(Ast_per90 × 2) +
(xG_overperformance × 0.5) +
(KP / 90s × 0.5)
```

This helps distinguish high-impact players beyond raw stats.

---

## 📚 Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly

Install all dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

---

## 📬 Contact

Created by **Ezekiel Loty**  
📧 ez276182@dal.ca  
🔗 [linkedin.com/in/ezekiel-loty](https://www.linkedin.com/in/ezekiel-loty/)
🐙 [github.com/EzekielLoty](https://github.com/EzekielLoty)

---

## 📝 License

This project is for educational and analytical purposes only.  
All data sourced from [FBref.com](https://fbref.com) under their fair use policy.

---
