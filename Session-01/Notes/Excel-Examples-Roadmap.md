# Excel for Data Analysis — Practical Examples Roadmap

## Section 1 — Excel Fundamentals

**Goal:** Learn basic Excel operations, formulas, and functions.

### Example 1: Basic Excel Functions
- Calculate the total sales using `SUM`.
- Calculate the average sales using `AVERAGE`.
- Find the highest and lowest sales using `MAX` and `MIN`.
- Count the number of sales records using `COUNT`.

**Dataset:**

| Employee | Sales |
|---|---:|
| Ali | 1200 |
| Sara | 1800 |
| Reza | 1500 |
| Mina | 2200 |
| Nima | 1300 |

**Tasks:**
1. Calculate total sales.
2. Calculate average sales.
3. Identify the employee with the highest sales.

### Example 2: AutoSum and RANDBETWEEN
- Use AutoSum to calculate total values.
- Generate random numbers using `RANDBETWEEN`.
- Create a sample dataset for practice.

---

## Section 2 — Data Management

**Goal:** Organize, clean, and manage datasets.

### Example 1: Data Cleaning
- Identify duplicate records.
- Find missing values.
- Correct inconsistent text formats.
- Remove unnecessary spaces using `TRIM`.

**Dataset:** Employee information containing names, departments, salaries, and dates.

### Example 2: Sorting and Filtering
- Sort employees by salary.
- Filter employees by department.
- Display employees with salaries greater than 30,000.

### Example 3: Conditional Functions
Use `IF`, `COUNTIF`, `SUMIF`, and `AVERAGEIF`.

**Task:** Categorize employees based on salary.

Example:
- Salary >= 40,000 → High Salary
- Salary < 40,000 → Standard Salary

---

## Section 3 — Data Visualization

**Goal:** Present data using meaningful charts.

### Example 1: Sales Dashboard
Create charts to compare monthly sales.

- Column Chart: Compare sales by month.
- Line Chart: Analyze sales trends.
- Pie Chart: Display sales distribution by category.

### Example 2: Employee Data Visualization
- Create a chart showing employee counts by department.
- Compare average salaries across departments.

### Example 3: Dashboard
Build a simple interactive dashboard using:
- PivotTables
- PivotCharts
- Slicers

---

## Section 4 — Descriptive Statistics

**Goal:** Summarize and understand numerical data.

### Example 1: Salary Analysis
Calculate:
- Mean
- Median
- Mode
- Range
- Variance
- Standard Deviation

**Dataset:**

| Employee | Salary |
|---|---:|
| A | 25000 |
| B | 30000 |
| C | 32000 |
| D | 35000 |
| E | 48000 |

### Example 2: Quartiles and Percentiles
- Calculate Q1, Q2, and Q3.
- Find the 90th percentile of salaries.
- Interpret the distribution of salaries.

### Example 3: Outlier Detection
Use the IQR method to identify unusually high or low salaries.

---

## Section 5 — Probability and Statistical Distributions

**Goal:** Understand probability concepts and statistical distributions.

### Example 1: Basic Probability
A company has 100 employees:
- 60 employees work in Department A.
- 40 employees work in Department B.

Calculate the probability of randomly selecting an employee from Department A.

### Example 2: Binomial Distribution
A quality-control process examines 10 products. Each product has a 5% probability of being defective.

Calculate the probability of finding exactly 2 defective products.

### Example 3: Normal Distribution
Assume employee salaries follow a normal distribution with:
- Mean = 35,000
- Standard Deviation = 5,000

Use `NORM.DIST` to calculate the probability that a salary is below 40,000.

---

## Section 6 — Statistical Analysis with XLStat

**Goal:** Perform statistical analyses using the XLStat add-in.

### Example 1: Descriptive Statistics
Analyze employee salaries and calculate:
- Mean
- Standard Deviation
- Quartiles
- Skewness
- Kurtosis

### Example 2: Normality Tests
Test whether employee salaries follow a normal distribution.

Methods:
- Shapiro–Wilk
- Anderson–Darling
- Lilliefors
- Jarque–Bera

### Example 3: Correlation Analysis
Investigate the relationship between:
- Salary and Starting Salary
- Salary and Previous Experience
- Salary and Job Tenure

### Example 4: Outlier Detection
Identify potential salary outliers using boxplots and statistical methods.

---

## Section 7 — Minitab

**Goal:** Conduct statistical analysis using Minitab.

### Example 1: Descriptive Statistics
Analyze a dataset containing employee salaries.

### Example 2: Normality Test
Determine whether the salary data are normally distributed.

### Example 3: Pearson Correlation
Investigate the relationship between salary and starting salary.

### Example 4: Regression Analysis
Explore whether starting salary and previous experience can help predict current salary.

---

# Session 2 — Advanced Statistical Analysis with Excel and XLStat

## Section 8 — Descriptive Statistics

### Example
Analyze the salaries of 10 employees.

Calculate:
- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Range

**Excel Functions:**
- `AVERAGE`
- `MEDIAN`
- `MODE.SNGL`
- `VAR.S`
- `STDEV.S`
- `MAX` and `MIN`

---

## Section 9 — Measures of Central Tendency

### Example
Given the following salaries:

25,000; 30,000; 30,000; 35,000; 40,000

Calculate:
- Mean
- Median
- Mode

Explain how these measures differ.

---

## Section 10 — Measures of Dispersion

### Example
Compare the salary variability of two departments.

| Department A | Department B |
|---:|---:|
| 25,000 | 20,000 |
| 30,000 | 30,000 |
| 35,000 | 40,000 |
| 30,000 | 50,000 |

Calculate and compare:
- Range
- Variance
- Standard Deviation

---

## Section 11 — Quartiles and Percentiles

### Example
Analyze employee salaries using quartiles.

Calculate:
- Q1
- Q2
- Q3
- 25th percentile
- 75th percentile
- 90th percentile

**Excel Functions:**
- `QUARTILE.INC`
- `PERCENTILE.INC`

---

## Section 12 — Outlier Detection

### Example
Identify potential outliers in the following salaries:

20,000; 22,000; 24,000; 25,000; 26,000; 28,000; 30,000; 95,000

Apply the IQR method.

Steps:
1. Calculate Q1 and Q3.
2. Calculate IQR.
3. Determine the lower and upper bounds.
4. Identify potential outliers.
5. Visualize the data using a Box Plot.

---

## Section 13 — Standardization and Normalization

### Example
Standardize employee salaries using Z-scores.

**Z-score:**

`Z = (X - Mean) / Standard Deviation`

Tasks:
1. Calculate the mean salary.
2. Calculate the standard deviation.
3. Calculate the Z-score for each employee.
4. Interpret positive and negative Z-scores.

For normalization, scale salary values between 0 and 1 using Min-Max normalization.

---

## Section 14 — Normality Tests

### Example
Test whether employee salaries follow a normal distribution.

Methods:
- Shapiro–Wilk
- Anderson–Darling
- Lilliefors
- Jarque–Bera

**Hypotheses:**

- H0: The data follow a normal distribution.
- H1: The data do not follow a normal distribution.

Interpret the p-value using a significance level of 0.05.

---

## Section 15 — Pearson Correlation

### Example
Investigate the relationship between current salary and starting salary.

| Employee | Starting Salary | Current Salary |
|---|---:|---:|
| A | 18000 | 25000 |
| B | 22000 | 30000 |
| C | 25000 | 35000 |
| D | 28000 | 40000 |
| E | 30000 | 45000 |

Tasks:
1. Calculate Pearson's correlation coefficient.
2. Interpret the direction and strength of the relationship.
3. Test statistical significance using XLStat.

**Excel Function:** `CORREL`

---

## Section 16 — Biserial Correlation

### Example
Investigate the relationship between employee salary and gender.

Variables:
- Salary: Quantitative variable
- Gender: Dichotomous variable

Tasks:
1. Encode the gender variable as a binary variable.
2. Perform biserial correlation analysis.
3. Interpret the correlation coefficient and p-value.

Note: The choice between point-biserial and biserial correlation depends on how the binary variable is defined.

---

## Section 17 — Frequency and Relative Frequency

### Example
Analyze the distribution of employees by department.

| Department | Frequency |
|---|---:|
| Sales | 30 |
| IT | 25 |
| HR | 15 |
| Finance | 30 |

Tasks:
1. Calculate frequency.
2. Calculate relative frequency.
3. Calculate percentage.
4. Create a frequency chart.

**Formula:**

`Relative Frequency = Frequency / Total Frequency`

---

## Section 18 — Scatter Plot and Box Plot

### Example 1: Scatter Plot
Visualize the relationship between:
- Starting Salary
- Current Salary

Interpret:
- Direction
- Strength
- Possible linear pattern

### Example 2: Box Plot
Visualize salary distribution.

Identify:
- Median
- Q1
- Q3
- IQR
- Potential outliers

---

## Final Project — Employee Salary Data Analysis

**Objective:** Perform a complete statistical analysis of an employee dataset.

### Project Steps
1. Import the dataset.
2. Clean and organize the data.
3. Perform descriptive statistics.
4. Calculate quartiles and percentiles.
5. Detect potential outliers.
6. Standardize and normalize numerical variables.
7. Conduct normality tests.
8. Analyze Pearson and biserial correlations.
9. Create Scatter Plots and Box Plots.
10. Interpret the results and prepare a final report.

### Tools
- Microsoft Excel
- XLStat
- Minitab

### Skills Developed
- Data Cleaning
- Descriptive Statistics
- Statistical Testing
- Correlation Analysis
- Data Visualization
- Statistical Interpretation
