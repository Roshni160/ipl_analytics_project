# IPL Cricket Analytics Dashboard- 2008 to 2020

**Domain:** Sports Analytics  
**Tools:** Python · Pandas · Matplotlib · Seaborn · Plotly

---

## Overview

13 seasons. 816 matches. 200,000+ deliveries. This project digs into IPL ball by ball data to uncover team performance patterns, batting & bowling trends, venue insights, and toss strategy delivered through 11 static charts and one fully interactive Plotly dashboard.

---

## Dataset

| Detail | Value |
|---|---|
| Source | [Kaggle — IPL Complete Dataset 2008–2020](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020) |
| Files | `IPL Matches 2008-2020.csv` + `IPL Ball-by-Ball 2008-2020.csv` |
| Matches | 816 |
| Deliveries | ~200,000+ |
| Seasons | 2008–2020 |

---

## Analysis Sections

### Team Performance
- All-time wins leaderboard
- Season-by-season win trends (top 5 teams)
- Toss decision strategy + win rate impact

### Batting Analysis
- Top 12 run scorers of all time
- Fours vs Sixes by team
- Average runs per ball, broken down by over and phase (Powerplay / Middle / Death)

### Bowling Analysis
- Top 12 wicket takers
- Dismissal type breakdown
- Economy rate by phase

### Season & Venue Trends
- Total runs scored per season (trend line)
- Top 10 venues by matches hosted

---

## Key Findings

| Insight | Detail |
|---|---|
| Most successful team | Mumbai Indians — 5 titles, most consistent across seasons |
| Toss strategy | Teams electing to field win ~55% — chasing is strategically preferred |
| Death overs | Over 19 has the highest avg runs/ball — batting-friendly at the death |
| Dominant dismissal | Caught accounts for 50%+ of all wickets |
| Run scoring trend | Total runs have increased season-on-season |
| Best chasing teams | Teams with strong lower-order batting excel in run chases |

---

## Output Files

| File | Description |
|---|---|
| `01_team_wins.png` | All-time wins bar chart |
| `02_season_wins.png` | Season-wise wins line chart |
| `03_toss_analysis.png` | Toss decision pie + win rate bar |
| `04_top_batsmen.png` | Top 12 run scorers |
| `05_boundaries.png` | Fours vs Sixes by team |
| `06_runs_by_over.png` | Avg runs per ball by over |
| `07_top_bowlers.png` | Top 12 wicket takers |
| `08_dismissal_types.png` | Dismissal breakdown pie |
| `09_economy_by_phase.png` | Economy rate by phase |
| `10_runs_per_season.png` | Total runs per season trend |
| `11_top_venues.png` | Venues by matches hosted |
| `ipl_dashboard.html` | **Full interactive Plotly dashboard** |

---

## Dependencies

```
pandas>=1.5
numpy>=1.23
matplotlib>=3.6
seaborn>=0.12
plotly>=5.10
kaleido>=0.2   # optional for static PNG export
```
