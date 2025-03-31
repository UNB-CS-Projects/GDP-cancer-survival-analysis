# GDP-cancer-survival-analysis
Using Descriptive and predictive Data Analytics to look at suspected correlation between two datasets

CS2704 Final Project

## Schedule
– Mar 29 (Sat): Submit proposal (individual submission)

– Apr 9 (Wed): Final presentation

– Apr 23 (Wed): Final report/presentation

## Group Members
- Christian Dennis

- Hadi Akbar

- Rudolph Stephen

## Hypothesis
**Brief Background**: 
GDP per capita could explain how well a country is equipped to provide advanced medical care for late-stage cancer patients, including access to cutting-edge treatments, specialized healthcare facilities, and early interventions.

**Statement**: 
The survival rate of late-stage cancer has a strong correlation with GDP per capita, suggesting that higher economic resources may contribute to better cancer treatment and improved patient outcomes.

**Challenges in Data Collection / Hypothesis Adjustment:**
Initially, we hypothesized that a countries GDP per capita strongly correlates with the survival rate of late-stage cancer, because wealthier countries are better equipped to provide advanced medical care. However, as we began collecting data, we found that reliable statistics specifically on late-stage cancer survival were difficult to obtain, making it challenging to test our hypothesis effectively. Given these limitations, we decided to broaden our focus to overall cancer survival rates rather than just late-stage cases. While this adjustment changes the specificity of our hypothesis, the core idea remains the same: higher economic resources may contribute to better cancer treatment and improved patient outcomes.

**New Statement**
The survival rate of general cancer diagnoses among both sexes has a strong correlation with GDP per capita, suggesting that higher economic resources may contribute to better overall cancer treatment and improved patient outcomes.

**Plan for testing Hypothesis**: 
Collect Data – Gather late-stage cancer survival rates (GCO, CONCORD) and GDP per capita (World Bank).
Merge & Clean Data – Standardize country names and handle missing values.
Analyze Correlation – Use Pearson correlation and linear regression to test the relationship.
Visualize Results – Create scatter plots and statistical summaries.
Interpret Findings – Assess significance (p < 0.05) and consider confounding factors.

## Data
Chosen Datasets:
- Used Files attached
- https://data.worldbank.org/indicator/NY.GDP.PCAP.CD | World Bank Group
- https://gco.iarc.fr/survival/survcan/dataviz/table | World Health Organization
