# What Went Wrong with the Toronto Blue Jays?
### A 2025 vs. 2026 Performance Analysis

**Python | pandas | NumPy | matplotlib | Jupyter Notebook | Data Analytics**

## Project Overview

After reaching the World Series in 2025, the Toronto Blue Jays experienced a significant decline in regular-season performance in 2026, falling from a 94–68 record to 79–83.

This independent data analytics project investigates the statistical factors associated with that decline through a comparison of team performance, individual players, defensive metrics, and roster changes.

The project follows the **Google Data Analytics framework: Ask, Prepare, Process, Analyze, Share, and Act**.

### Research Question

**What statistical factors contributed to the Toronto Blue Jays' decline between the 2025 and 2026 MLB seasons?**

## Tools and Technologies

- **Python:** Data cleaning, calculations, and analysis
- **pandas:** Data manipulation, filtering, and aggregation
- **NumPy:** Numerical operations
- **matplotlib:** Data visualization
- **JupyterLab:** Interactive analysis and documentation
- **CSV:** Raw and processed datasets

## Methodology

The analysis was organized into six Jupyter notebooks:

| Notebook | Description |
|---|---|
| [01 — Data Processing](Notebooks/01_Process.ipynb) | Cleaning and preparing datasets |
| [02 — Offensive Analysis](Notebooks/02_Offensive_Analysis.ipynb) | Comparing team and player offensive production |
| [03 — Pitching Analysis](Notebooks/03_Pitching_Analysis.ipynb) | Evaluating run prevention and pitching personnel |
| [04 — Fielding Analysis](Notebooks/04_Fielding_Analysis.ipynb) | Examining traditional and advanced defensive metrics |
| [05 — Roster Analysis](Notebooks/05_Roster_Analysis.ipynb) | Investigating roster turnover and player participation |
| [06 — Final Summary](Notebooks/06_Final_Summary.ipynb) | Integrating findings and drawing conclusions |

## Key Findings

### 1. Offensive Decline Was the Primary Factor

Toronto's offensive production deteriorated substantially between seasons.

| Metric | 2025 | 2026 | Change |
|---|---:|---:|---:|
| Runs Scored | 798 | 648 | -150 |
| Home Runs | 191 | 152 | -39 |
| OPS | .761 | .692 | -.069 |

Eight of nine returning hitters with at least 150 plate appearances in both seasons recorded declining OPS.

The findings indicate that reduced production among returning players was a major component of Toronto's offensive decline.

### 2. Overall Pitching Improved

Despite the worsening win-loss record, Toronto's run prevention improved.

| Metric | 2025 | 2026 |
|---|---:|---:|
| Runs Allowed | 721 | 694 |
| ERA | 4.19 | 3.89 |

Several returning pitchers experienced declining individual performance, but improvements elsewhere on the pitching staff contributed to better overall results.

### 3. Defensive Performance Was Mixed

Traditional fielding statistics deteriorated, while advanced defensive metrics improved.

- Errors increased from 86 to 99.
- Fielding percentage declined from .985 to .983.
- Defensive Runs Saved improved from +4 to +33.
- Total Zone Runs improved from -8 to +8.

These results suggest that defensive performance cannot be evaluated using errors alone.

### 4. Roster Turnover and Player Availability

Of the 58 players who appeared for Toronto in 2025, only 25 returned in 2026.

Injuries, roster departures, and changes in playing time affected the composition of the team.

The analysis also identified significant changes in offensive contributions among returning players compared with players appearing in only one season.

## Overall Results

| Metric | 2025 | 2026 | Change |
|---|---:|---:|---:|
| Wins | 94 | 79 | -15 |
| Losses | 68 | 83 | +15 |
| Runs Scored | 798 | 648 | -150 |
| Runs Allowed | 721 | 694 | -27 |
| Run Differential | +77 | -46 | -123 |

The 123-run deterioration in run differential was primarily driven by the loss of 150 runs of offensive production. Improved run prevention partially offset this decline.

## Conclusion

**Toronto's decline was primarily associated with reduced offensive production, particularly among returning hitters, rather than deterioration in overall pitching performance.**

Although pitching and several advanced defensive metrics improved in 2026, these improvements were insufficient to compensate for the substantial offensive regression.

Roster turnover and player availability provided additional context for the team's changing performance.

## Limitations

- The analysis compares two seasons and identifies statistical relationships rather than establishing definitive causation.
- Player comparisons use minimum playing-time thresholds, potentially excluding smaller contributors.
- Roster participation and injury-related context do not independently measure the causal impact of injuries.
- A two-earned-run discrepancy was identified between the 2026 player-level pitching totals and the team-level data and documented in the pitching notebook.

## Data and Reproducibility

Original datasets are stored in `data/raw/`, with cleaned datasets in `data/processed/`.

The notebooks use relative file paths and are intended to be run from the `Notebooks/` directory, beginning with `01_Process.ipynb`.

The analysis uses Python, pandas, NumPy, and matplotlib. The exact dataset sources and package setup instructions will be documented before final publication.

## Author

**Alberto Izaguirre**

Mathematics Graduate, York University  
Google Data Analytics Professional Certificate

*Independent data analytics portfolio project.*