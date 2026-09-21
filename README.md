# Project Title: one-line description

> **In one sentence:** what I found and why it matters to the business.

## Business Question
<!-- One sentence a non-technical manager would recognize. Who needs to decide what? -->

## Data
- **Source:** <!-- name, link, licence -->
- **Size:** <!-- rows, tables, period covered -->
- **Notes:** <!-- real or synthetic, known quirks. Raw data is not stored in this repo -->

## Method
<!-- 1. Cleaning (link the cleaning log)
     2. Analysis (link to sql/ and notebooks/)
     3. Visualization -->

**Tools:** PostgreSQL, Python (pandas, SQLAlchemy, matplotlib)

## Key Findings
<!-- Each finding is one sentence with a number, plus a chart if it helps. -->
1. **Finding with a number.**
2. **Finding with a number.**
3. **Finding with a number.**

## Recommendations
<!-- What should the business do, and what impact do you expect? -->

## Limitations
<!-- Data caveats and what this analysis cannot tell you. -->

## How to reproduce
1. Clone the repo and create the environment: `python -m venv .venv`, then `pip install -r requirements.txt`
2. Download the data from <!-- link --> into `data/raw/`
3. Run the SQL scripts in `sql/` in order, then the notebooks in `notebooks/`

## Repository structure
- `data/` : raw and processed data (not tracked in Git)
- `sql/` : numbered, documented queries
- `notebooks/` : cleaning and analysis notebooks
- `reports/` : charts, dashboards and the written summary