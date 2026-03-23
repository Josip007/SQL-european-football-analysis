# European Football Analysis

Exploratory analysis of 25,000+ football matches across 11 European leagues (2008–2016) using SQL and Python.

## Questions Answered
- Which Premier League teams had the highest win rate?
- Does home advantage exist across all leagues?
- Are matches becoming more goal-rich over time?
- Which teams had the longest winning streaks?
- Which teams were most consistent season over season?
- How do Premier League, La Liga and Bundesliga compare?

## Key Findings
- Manchester United dominated Premier League with 63.2% win rate (2008–2016)
- FC Barcelona (77%) and Real Madrid (75%) show La Liga is a two-horse race
- Home advantage exists in every league — Spain strongest (48.8%), Scotland weakest (41.7%)
- Average goals per match grew slightly from 2.61 to 2.75 over 8 seasons
- Arsenal: best combination of high performance (55.9%) and consistency across seasons

## Tech Stack
- **SQL** — CTEs, window functions, JOINs, aggregations
- **Python** — pandas, matplotlib
- **Database** — SQLite (European Soccer Database, Kaggle)

## Dataset
[European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer) — Kaggle  
Note: `database.sqlite` not included (305MB). Download from Kaggle link above.

## How to Run
1. Download `database.sqlite` from Kaggle
2. Place it in the project root
3. Update path in notebook Cell 3 to your local path
4. Run all cells top to bottom