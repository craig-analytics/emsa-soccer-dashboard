# ⚽ EMSA Youth Soccer League Dashboard – Excel Project

This is my **first self-guided analytics project**, built entirely from scratch using real data from my son's U9 soccer league. The league shares match scores but does **not publish team standings** for divisions under age 10. I created this dashboard to analyze team performance, calculate points, and track standings.

---

## 🔍 Project Overview

- Designed in **Microsoft Excel** with auto-calculated standings
- Built to simulate a live league table (3 pts for a win, 1 for draw)
- Structured into 3 clear tabs:
  - **Data**: manual score input
  - **Helper**: logic & calculations (date/time, match status)
  - **Dashboard**: team stats and rankings

---

## 📊 Features

- Manual match score entry from league website
- Auto-computed:
  - Points, GF, GA, GD
  - Win %, Avg Goals per Game
  - Match status using `NOW()` to **exclude future matches** from points calculations
- Ranking logic using `RANK.EQ` with `COUNTIFS` for tie-breaking
- Interactive **PivotTable** and **Slicer** for team filtering
- “Last Updated” timestamp
- Clean layout designed for parents, coaches, and personal development

---

## 🧠 Learning Outcome

- Gained hands-on experience applying **data logic**, formulas, and layout structuring in Excel
- Used `NOW()` to build time-sensitive logic that prevents future matches from skewing stats
- Reinforced transition skills from logistics/supply chain into business intelligence
- Built independently — **without tutorials or pre-built templates**

---

## ⚠️ Limitations

- EMSA’s website displays scores using JavaScript, which blocks Excel’s Power Query from importing data via “Get Data from Web”
- All match scores are **entered manually** after each game day (copied from website)
- Future automation could involve tools like **Octoparse**, **Selenium**, or **API access (if available)**

---

## ✅ Ethical Disclosure

- All data used in this project is publicly available via the EMSA website.
- **Team names have been anonymized** to protect the privacy of youth participants.
- This project is intended solely for learning, portfolio use, and to demonstrate real-world BI logic using publicly viewable match results.

---

## 🛠 Tools Used

- Microsoft Excel:  
  `SUMIF`, `IF`, `NOW`, `RANK.EQ`, `COUNTIFS`, `PivotTables`, `Slicers`, Conditional Formatting

---

