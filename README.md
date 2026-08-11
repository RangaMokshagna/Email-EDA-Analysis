# Personal Email EDA

End-to-end exploratory data analysis on a 26,871-message, 4.6-year Gmail archive, built from a raw `.mbox` export.

## Highlights

- Diagnosed and fixed a 99.32% data-loss bug in date parsing caused by pandas 2.0 datetime parsing changes
- Engineered engagement features from Gmail metadata and analyzed unread behavior
- Measured statistically significant email-volume trends over time
- Explored sender concentration with Pareto-style analysis

## Stack

Python, pandas, NumPy, Matplotlib, Seaborn, SciPy

## Privacy Note

Raw mailbox exports, extracted CSV files, generated personal figures, and notebook outputs are excluded from this repository for privacy. See `project.ipynb` for the full pipeline and analysis code.
