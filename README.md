# 📺 JV YouTube — Trending Dashboard

An end-to-end data visualization project analyzing YouTube trending video patterns across five global regions, using Tableau to uncover category dynamics and temporal trends.

---

## 🔍 Overview

This project explores a real-world dataset of YouTube trending videos, tracking how content categories rise and fall in popularity across different countries over time. The interactive Tableau dashboard allows users to filter by region, category, and date — enabling dynamic comparisons and storytelling through data.

**Regions covered:** France, India, Japan, Russia, United States

**Dataset:** `trending_by_time.csv` — containing ~12,000+ records with fields for region, trending date, content category, and video count.

---

## 📊 What's Inside the Dashboard

### 1. Video Trends by Country
A time-series view showing the volume of trending videos per region over time. Allows direct comparison of how different countries' audiences consume content at a given moment.

### 2. Videos by Date and Category
A breakdown of trending video counts by content category across the full timeline. Highlights which categories dominate trending sections and how their presence evolves month by month.

### 3. Category Share (% of Total)
A percentage-based view of the same data — normalizing volume differences between regions to reveal the **relative dominance** of each category per market.

> All three sheets are fully interactive and linked through dashboard actions — clicking any data point filters the rest of the view in real time.

---

## 🔑 Key Insights

- **Entertainment and Music** consistently dominate trending sections across all five regions, though their relative weight differs by country.
- **Japan** shows a distinctly different content distribution compared to Western markets — with stronger representation of categories like Gaming and Anime-adjacent content.
- **India** exhibits high volatility in category trends, reflecting a rapidly evolving digital content market.
- The **% of Total** view reveals that what looks like a dominant category by volume isn't always dominant by share — useful for market-specific strategy decisions.

---

## 🛠️ Tech Stack

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![CSV](https://img.shields.io/badge/Data-CSV-blue?style=flat)

---

## 🚀 View the Dashboard

🔗 [Open Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Youtube_17767038459110/Dashboard1)

---

## 📁 Repository Structure

```
JV-YouTube/
│
├── Youtube.twb          # Tableau workbook file
├── README.md            # Project documentation
```

---

## ⚙️ Setup

To explore the workbook locally:

1. Clone the repo
```bash
git clone https://github.com/franciscojvazquezp/JV-YouTube.git
cd JV-YouTube
```

2. Open the workbook
```
Open Youtube.twb in Tableau Desktop (version 2026.1 or later recommended)
```

> Note: The dashboard uses an embedded data extract. No external CSV required.

---

👤 Author: franciscojvazquezp

