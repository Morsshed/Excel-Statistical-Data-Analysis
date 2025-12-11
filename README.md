# Excel-Statistical-Data-Analysis
Statistical Analysis

## Descriptive Statistics
![Descriptive Statistics Example](https://raw.githubusercontent.com/Morsshed/Excel-Statistical-Data-Analysis/main/ExcelImages/Descriptive%20Statistics.png)

| Metric                 | Meaning                                |
| ---------------------- | -------------------------------------- |
| **Mean** (Average)     | The central value in the dataset       |
| **Median**             | The middle value when data are ordered |
| **Mode**               | The most frequent value                |
| **Standard Deviation** | How spread out the data are            |
| **Variance**           | The square of the standard deviation   |
| **Range**              | Difference between max and min         |
| **Minimum / Maximum**  | Smallest and largest values            |
| **Count**              | Number of observations                 |
| **Sum**                | Total of all values                    |


## Correlation Analysis
![Correlation Analysis Example](https://raw.githubusercontent.com/Morsshed/Excel-Statistical-Data-Analysis/main/ExcelImages/Correlation.png)

Correlation tells you how two sets of data are related.

The most common metric is the Pearson correlation coefficient, which ranges from -1 to +1:

+1 → perfect positive relationship (both variables increase together)

0 → no linear relationship

-1 → perfect negative relationship (one increases as the other decreases)

###### Correlation 
                   CORREL(range1, range2)
                   
| Correlation Value | Interpretation                 |
| ----------------- | ------------------------------ |
| **0.85**          | Strong positive relationship   |
| **0.30**          | Weak positive relationship     |
| **-0.50**         | Moderate negative relationship |
| **-0.90**         | Strong negative relationship   |


## Regression Analysis
![Regression Analysis Example](https://raw.githubusercontent.com/Morsshed/Excel-Statistical-Data-Analysis/main/ExcelImages/Regression.png)

###### Linear Regression
                   Y = a + bX

                   | Metric              |  Meaning                                                    |
| ------------------- | ------------------------------------------------------------- |
| **Coefficient (b)** | For every $1 increase in advertising, sales increase by $0.50 |
| **R-Squared**       | 0.75 → 75% of sales variability explained by advertising      |
| **p-value**         | Determines significance of the relationship                   |


## Anova Test
![ANOVA Analysis Example](https://raw.githubusercontent.com/Morsshed/Excel-Statistical-Data-Analysis/main/ExcelImages/Anova.png)

A high F-value and low p-value (typically < 0.05) suggest the group means are significantly different

                   | Metric                    | Meaning                                                   |
| ------------------------- | --------------------------------------------------------- |
| **Between Groups**        | Variation due to the factor being tested (e.g., category) |
| **Within Groups (Error)** | Variation within each group                               |
| **F-Statistic**           | Ratio of between-group to within-group variance           |
| **p-Value**               | Probability that observed differences occurred by chance  |
| **Significance**          | Indicates whether group means differ meaningfully         |

