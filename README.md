# Data Science Portfolio

Selected, polished data analysis projects demonstrating statistical reasoning, SQL, Python, and Power BI applied to real questions. For self-directed learning logs and coursework, see [python-sql-fundamentals](https://github.com/JacobGensemer/python-sql-fundamentals) and [DTSA_5301](https://github.com/JacobGensemer/DTSA_5301).

## Projects

### NBA Usage Rate vs. Shooting Efficiency
`nba_usage_efficiency_analysis.ipynb`

Tests a common basketball analytics narrative, that higher usage rate trades off against shooting efficiency, using 2024-25 NBA season data. Diagnosed and corrected a dataset mismatch, applied appropriate sample-size filtering, and used correlation, a two-sample t-test, and a multiple regression controlling for minutes played to find no statistically significant relationship, a finding that held up under multiple methods.

### Portfolio Diversification and Risk-Adjusted Returns
`portfolio_diversification_analysis.ipynb`

Tests whether concentrated stock portfolios outperform diversified ones, using real historical price data pulled via the Yahoo Finance API and analyzed primarily in SQL, window functions, joins, and CTEs, calculating daily returns and portfolio-level performance. Found that concentration's apparent advantage depends heavily on both market regime (bull market vs. financial crisis) and sector choice, not a fixed edge.

### NHL Expected Goals Dashboard
`nhl-xg-dashboard/`

Tests whether NHL teams score what their expected goals (xG) say they should, using 18 seasons of MoneyPuck team data (554 team seasons). Built a Power BI dashboard (Power Query pipeline, one to many data model, DAX measures) and a Python regression in `nhl_xg_analysis.ipynb`. Goal share moves roughly one for one with xG share (slope 1.07, R squared 0.59). A few teams, such as Boston and San Jose, finish above or below their xG in most seasons, but the data cannot say why, so the analysis describes the gap without explaining it. Data and xG model: MoneyPuck.com.