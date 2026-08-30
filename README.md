# Data Science Portfolio

Personal projects and coursework built while pursuing an MS in Data Science (CU Boulder, Coursera) and preparing for a career in data science and AI. This repo tracks a self-directed Python sprint alongside formal coursework, with the goal of building real, applied fluency beyond what any single class covers.

## Environment

- Python 3.11, managed with Miniconda (`dsprint` environment)
- WSL2 (Ubuntu) on Windows
- VS Code with Jupyter

## Progress Log

**Day 1**: Python fundamentals, variables and core data types, control flow (if/elif/else), function definition and calls. Built and debugged a score classification function.

**Day 2**: Data structures, lists and dictionaries, list and dictionary comprehensions. Built a filtering comprehension combining membership checks with conditional logic.

**Day 3**: NumPy fundamentals, array creation, vectorized operations, boolean masking, 2D array indexing and axis-based aggregation. Solved a multi-step exercise finding per-student averages and filtering failing scores.

**Day 4**: Pandas fundamentals, DataFrame creation, column and row selection with loc and iloc, boolean filtering, adding computed columns, groupby aggregation, and sorting. Debugged real syntax errors involving method calls versus references and multi-argument loc indexing.

**Day 5**: Pandas merging and joins (inner, left, outer), detecting and handling missing data with isna, fillna, and dropna. Chained multiple merges together and made deliberate column-specific decisions about filling versus preserving missing values.

**Day 6**: Data visualization with matplotlib and seaborn, bar charts and scatter plots. Layered matplotlib reference lines and labels on top of seaborn plots to mark a passing threshold visually.

**Day 7**: Statistical inference in Python using scipy, descriptive statistics, confidence intervals, and one-sample hypothesis testing. Caught and corrected a one-sided versus two-sided testing error by cross-checking a p-value against a confidence interval and t-statistic.
## Structure

Each day's work lives in its own notebook (`day1.ipynb`, `day2.ipynb`, etc.), building sequentially on prior concepts and coursework.