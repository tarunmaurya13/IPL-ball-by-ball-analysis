# 🏏 IPL Ball-by-Ball Analysis Project

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-orange.svg)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

---

## 📌 Project Overview

This project is a comprehensive, end-to-end exploratory data analysis (EDA) of the **IPL Ball-by-Ball dataset** — one of the most granular cricket datasets available. Every single delivery bowled across **577 IPL matches** has been analyzed to uncover patterns, records, and insights that go beyond the scoreboard.

The project follows a **story-driven, question-answer format** — starting from raw data and building up to a final Dream Playing XI selection based purely on statistical evidence.

---

## 🎯 Objectives

- Clean and preprocess raw ball-by-ball IPL data
- Identify run-scoring patterns across game phases
- Rank the best batsmen, bowlers, and partnerships
- Analyze match-winning trends (batting first vs second)
- Visualize bowler vs batsman dominance using heatmaps
- Build a data-driven Dream Playing XI

---

## 📂 Dataset Information

| Property | Details |
|---|---|
| **File** | `IPL DataSet - Ball_by_Ball Cleaned.csv` |
| **Total Deliveries** | 1,36,590 |
| **Total Matches** | 577 |
| **Total Batsmen** | 434 |
| **Total Bowlers** | 331 |
| **Total Columns** | 19 |

### Columns Description

| Column | Description |
|---|---|
| `Match_Id` | Unique identifier for each match |
| `Innings_Id` | Innings number (1 or 2) |
| `Over_Id` | Over number (1–20) |
| `Ball_Id` | Ball number within the over |
| `Team_Batting_Id` | Batting team identifier |
| `Team_Bowling_Id` | Bowling team identifier |
| `Striker_Id` | Batsman on strike |
| `Striker_Batting_Position` | Batting position (1–11) |
| `Non_Striker_Id` | Batsman at non-striker end |
| `Bowler_Id` | Bowler identifier |
| `Batsman_Scored` | Runs scored off the bat |
| `Extra_Type` | Type of extra (Wide, No-ball, etc.) |
| `Extra_Runs` | Extra runs conceded |
| `Player_dissmial_id` | Dismissed player ID (0 = not out) |
| `Dissimal_Type` | Mode of dismissal |
| `Fielder_id` | Fielder involved in dismissal |
| `Match_Winner_Id` | Winning team identifier |
| `Strike_Rate` | Calculated strike rate |
| `Total_Runs` | Batsman runs + Extra runs |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `Pandas` | Data loading, cleaning, manipulation |
| `NumPy` | Numerical operations |
| `Matplotlib` | Base plotting and chart customization |
| `Seaborn` | Statistical visualizations and styling |
| `Google Colab` | Cloud-based notebook environment |

---

## 📊 Project Structure — 26 Questions across 8 Chapters

### Chapter 1 — Understanding the Data
- Q1. What does the dataset look like?
- Q2. How clean is the data?

### Chapter 2 — Run Scoring Patterns
- Q3. Which game phase scores the most runs?
- Q4. Which over is the most explosive?
- Q5. What is the most common score off a single ball?
- Q6. How does run scoring change ball-by-ball within an over?

### Chapter 3 — Batting Analysis
- Q7. Who are the Top 10 run-scorers?
- Q8. Who has the best Strike Rate?
- Q9. Which batting position scores the most runs?
- Q10. Who are the best finishers in death overs?

### Chapter 4 — Bowling Analysis
- Q11. Who are the Top 10 wicket-takers?
- Q12. Who are the most economical bowlers?
- Q13. Which over do bowlers take the most wickets?
- Q14. Who are the most dangerous death over bowlers?

### Chapter 5 — Extras & Dismissals
- Q15. How are extras distributed?
- Q16. What is the most common way to get dismissed?
- Q17. Which over sees the most wickets fall?

### Chapter 6 — Match & Team Analysis
- Q18. Does batting first or second win more matches?
- Q19. How do teams perform in 1st vs 2nd innings?
- Q20. Which team is the most consistent run-scorer?

### Chapter 7 — Records & Milestones
- Q21. What is the highest partnership in IPL?
- Q22. Which bowler has the best single match performance?
- Q23. Which match had the highest total runs scored?

### Chapter 8 — The Final Verdict
- Q24. What does the perfect IPL batsman look like?
- Q25. What does the perfect IPL bowler look like?
- Q26. Which Bowler-Batsman matchup is the most dominant? *(Heatmap)*

---

## 📈 Key Visualizations

| Chart Type | Used For |
|---|---|
| Bar Chart (Vertical) | Run distribution, phase analysis, dismissals |
| Bar Chart (Horizontal) | Player rankings, team comparisons |
| Line Chart + Fill | Ball-by-ball trends, wickets per over |
| Pie Chart | Extra types, match win analysis |
| Scatter Plot | Batsman & bowler profiles |
| Heatmap | Bowler vs Batsman dominance map |

---

## 🔍 Key Insights

- **Powerplay (overs 1–6)** is the most attacking phase with highest run rate
- **Dot balls** account for over **50%** of all deliveries
- **Caught** is by far the most common dismissal type
- **Batting second** wins slightly more matches than batting first
- **Wides** are the most common extra in IPL
- The **last 2 overs** see the highest run rate and most wickets

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the dataset `IPL DataSet - Ball_by_Ball Cleaned.csv`
3. Run each cell in order from **Q1 to Q26**
4. Each question is self-contained in its own cell

```python
# Required libraries (pre-installed in Colab)
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📁 File Structure

```
IPL-Analysis/
│
├── IPL Analysis Practice.ipynb     ← Main notebook (26 questions)
├── IPL DataSet - Ball_by_Ball Cleaned.csv  ← Dataset
└── README.md                       ← Project documentation
```

---

## 👤 Author

> This project was built as part of a data analysis learning journey using Python, Pandas, NumPy, Matplotlib and Seaborn — progressing from basic EDA to advanced visual storytelling.

---

## 📜 License

This project is open source and available for educational purposes.

---

*"In God we trust. All others must bring data."* — W. Edwards Deming 🏏
