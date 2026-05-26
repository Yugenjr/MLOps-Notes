# Exploratory Data Analysis (EDA) - 50 Line Notes

## Definition
Exploratory Data Analysis (EDA) is the critical first step in data science projects. It involves analyzing datasets to discover patterns, detect anomalies, understand relationships, and validate assumptions before building predictive models or drawing conclusions.

## Objectives of EDA
- Understand data structure, size, and composition
- Identify missing values, duplicates, and outliers
- Discover patterns and relationships between variables
- Validate data quality and consistency
- Generate initial hypotheses for further investigation
- Inform feature engineering and preprocessing decisions
- Communicate data insights to stakeholders

## Key Components

### 1. Data Overview
- Check dataset shape (rows, columns)
- Review data types of each column
- Examine first/last rows with `head()` and `tail()`
- Get summary statistics with `describe()`
- Identify data sources and collection methods

### 2. Missing Data Analysis
- Count missing values per column
- Calculate percentage of missing data
- Identify patterns in missing data
- Determine handling strategy: drop, impute, or flag
- Visualize missing data distribution

### 3. Univariate Analysis
- Analyze individual variables independently
- For numerical: mean, median, std dev, min, max, quartiles
- For categorical: frequency, mode, unique values
- Create histograms for numerical data distribution
- Create bar charts for categorical data distribution
- Identify skewness and kurtosis in distributions

### 4. Bivariate Analysis
- Examine relationships between two variables
- Use scatter plots for numerical-numerical relationships
- Use box plots for categorical-numerical relationships
- Create crosstabs for categorical-categorical relationships
- Calculate correlation coefficients (Pearson, Spearman)
- Identify strong correlations and dependencies

### 5. Multivariate Analysis
- Examine relationships among multiple variables
- Create correlation heatmaps
- Use pair plots for comprehensive relationships
- Perform dimensionality reduction techniques
- Identify feature interactions and dependencies
- Use clustering to find natural groupings

## Outlier Detection
- Statistical methods: z-score, IQR method
- Visual inspection: box plots, scatter plots
- Machine learning methods: isolation forest, local outliers
- Evaluate impact: keep, remove, or transform outliers
- Document outlier handling decisions

## Data Quality Checks
- Validate data types match expected values
- Check for impossible values (negative ages, dates in future)
- Verify data ranges and constraints
- Identify duplicated records
- Cross-validate related fields for consistency
- Check for encoding issues in text fields

## Statistical Summary
- Central tendency: mean, median, mode
- Dispersion: range, variance, standard deviation
- Distribution shape: skewness, kurtosis
- Percentiles and quartiles for understanding spread
- Comparisons across groups and segments

## Visualization Techniques
- Histograms for distribution visualization
- Box plots for outliers and quartiles
- Scatter plots for relationships
- Heatmaps for correlations
- Bar charts for categorical comparisons
- Line plots for time series data
- Pair plots for multiple variables
- Density plots for probability distributions

## Documentation
- Create data dictionary with column descriptions
- Document data collection methodology
- Record assumptions and limitations
- Note anomalies and data quality issues
- Track all preprocessing decisions
- Maintain EDA findings in reports

## Tools & Libraries
- Python: Pandas, NumPy, Matplotlib, Seaborn, Plotly
- R: dplyr, ggplot2, plotly
- SQL: for large databases
- Tableau/Power BI: for interactive dashboards
- Jupyter Notebooks: for reproducible analysis

## Common EDA Mistakes
- Skipping EDA and jumping to modeling
- Not handling missing data appropriately
- Ignoring outliers without investigation
- Over-complicating initial analysis
- Drawing conclusions from visual inspection alone
- Not validating data quality
- Ignoring domain context

## EDA Output Deliverables
- Summary statistics tables
- Visualization dashboard
- Data quality report
- Feature importance insights
- Recommendations for preprocessing
- Identified risks and limitations
- Hypotheses for modeling

## Conclusion
EDA is foundational for data-driven decision making. It ensures data quality, builds intuition about data, informs feature engineering, and prevents costly modeling mistakes. Invest time in thorough EDA before building models.
