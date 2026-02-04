# Data Analysis Summary - Football Player Scores

## 1. Research Question
What factors are most strongly associated with player Rating?

## 2. Dataset Overview
- ~18,979 players
- 78 variables (numeric + categorical)
- Target variable: Rating (0–100)

## 3. Data Quality Assurance & Cleaning
I performed comprehensive data cleaning and QA to ensure reliable analysis.

- Removed irrelevant index-like and URL columns
- Fixed formatting issues and inconsistent strings
- Corrected scaling errors (values exceeding expected ranges)
- Standardized physical attributes (Height → cm, Weight → kg)
- Parsed currency fields (MarketValue, WeeklyWage, ReleaseClause)
- Resolved overlapping contract information and created an OnLoan indicator
- Handled missing values and cleaned popularity-related signals

## 4. Exploratory Data Analysis (EDA)

### Insight 1 — Rating vs BestOverall
Rating shows a strong positive relationship with BestOverall, indicating that
higher overall skill metrics align closely with player ratings.

### Insight 2 — Rating, MarketValue, and Age
Market value increases sharply for players with ratings above ~80.
High-rated players tend to cluster around peak performance ages
(mid-20s to early-30s).

## 5. Key Takeaways
- Rating is strongly driven by overall performance metrics
- High ratings correlate with higher market value and peak-age players
- Thorough data cleaning is critical for meaningful player evaluation
