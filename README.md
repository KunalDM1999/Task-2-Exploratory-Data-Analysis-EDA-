# Task-2-Exploratory-Data-Analysis-EDA-

1 Loaded and Inspected Data – Used pandas and numpy to check data shape, nulls, and basic info.

2 Handled Missing Values – Filled nulls using label-based filling and median (no coding needed now).

3 Explored Numeric Features – Used seaborn and matplotlib to find that Value, Wage, and Release Clause are skewed and have outliers.

4 Checked Relationships – Used pairplot and correlation heatmap; found strong linear relation between Value, Wage, and Release Clause.

5 Categorical Feature Analysis – Used countplots and boxplots; found most players use right foot, top positions are ST/GK/CB, England has the most players.

6 Encoded Categorical Columns –

a Binary Encoding for Preferred Foot

b Frequency Encoding for Position, Nationality

c Kept Club with "Other" label for rare/null entries

7 Dropped ID and Name – Too many unique values, not useful for modeling.

8 Fixed Skewness – Applied log1p transformation on Value, Wage, Release Clause.

9 Feature Scaling – Used StandardScaler to normalize numeric features.

10 Final Dataset Ready – Clean, numeric, scaled, no nulls – ready for ML modeling.
