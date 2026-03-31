# UCSD Men's Basketball: Performance & Matchup Analysis
A data-driven investigation into UCSD's 2025-2026 season: quantifying pace vulenrability, diagnosing the mid-season drop-off, and identifying optimal matchup conditions using advanced efficiency metrics.

---

## Motivation
As an avid Tritons hoops fan, I attended almost all of the home games and multiple away games, even traveling to Henderson, NV to watch the Big West conference tournament. As I watched the 2025-2026 season progress, I and many others noticed something that we couldn't exactly articulate: a sharp decline in the men's team's performance as conference play began. Teams that played at a faster pace seemed to expose something structural in UCSD's game.

This project attempts to put numbers to that observation using KenPom-style efficiency metrics and Four Factors analysis.

---

## Key Questions
- Does UCSD's defensive efficiency measurably decline when opponents play at a high tempo?
- After controlling for opponent quality, did UCSD's underlying performance actually deteriorate over the season?
- Which of Dean Oliver's Four Factors (Effective Field Goal Percentage, Turnover Percentage, Offensive Rebounding Percentage, Free Throw Rate) broke down most consistently in losses?
- What does an ideal matchup look like for this team, and what conditions predict a loss?

---

## Season Snapshot

---

## Tech Stack
- **Scraping:** `requests`, `BeautifulSoup`
- **Analysis:** `pandas`, `numpy`
- **Modeling:** `scikit-learn`, `XGBoost`
- **Visualization:** `Plotly`, `Streamlit` (TBD)
---
## Project Structure
```
ucsd-basketball/
├── data/
│   ├── raw/          # scraped CSVs
│   └── processed/    # cleaned, enriched datasets
├── notebooks/
│   ├── 01_scraping.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_pace_analysis.ipynb
│   └── 04_modeling.ipynb
└── README.md
```

---

## Findings

*To be updated as analysis progresses.*

---

### Reproducting This Project
```bash
git clone https://github.com/esokite3/ucsd-basketball-analysis
cd ucsd-basketball-analysis
pip install -r requirements.txt
jupyter notebook notebooks/01_scraping.ipnyb
```