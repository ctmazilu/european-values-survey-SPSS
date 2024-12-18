# Univariate and Bivariate Analysis of European Values Survey, 2018 using SPSS

# Introduction
Using the European Values Study for Great Britain (ESV, 2018) in SPSS to answer the Research Question: Is there a relationship between perceived quality of democratic political system and perceived women rights compared to men.

## Index
- [Introduction](#introduction)
  - [Research Question](#research-question)
  - [Rationale](#rationale)
  - [Hypothesis](#hypothesis)
- [Data Description](#data-description)
  - [Variable description](#variable-description)
- [Analysis](#analysis)
  - [Univariate Analysis](#univariate-Analysis)
  - [Bivariate Analysis](#bivariate-analysis)
- [Conclusion](#conclusion)
  - [References](#references)
  - [Copyright](#copyright)

  
## Reseach Question

**Research Question**: Is there a relationship between perceived quality of democratic political system and perceived women rights compared to men.

## Rationale

Why is this question sociologically relevant and interesting? 

This question will answer if the quality of the democratic political system influences equal rights between men and women. This is sociologically interesting because it answers two fundamental aspects of society, gender, and politics. It seeks to understand whether democracy benefits gender equality. Sociology of gender and Political Sociology are interesting and relevant fields.

The level of gender equality could be seen as a measure of a democracy’s quality. Democracies that uphold equal rights for all citizens, regardless of gender, may be considered ‘better’ or effective.

It must be kept in mind that the data is not inclusive of all gender identity, and this could be explored in further collection of data (i.e. does perceived quality of democratic political system influence if trans/non-binary people have the same (perceived) rights as men and women.). This research question can strengthen our understanding of political systems as a social institution with large capabilities for social change.

## Hypothesis 
Both variables are *ordinal* therefore a *crosstabulation* will be conducted. It could go both ways, democracy could influence womenrights;womenrights could influence democracy.

> **Independent variable:** democracy
> 
> **Dependent variable:** womenrightsRecode

**Null Hypothesis H0:** There is no significant relationship between perceived quality of democratic political system and perceived women rights compared to men.
**Alternative Hypothesis H1:** There is a significantrelationshipbetweenperceivedqualityofdemocratic political system and perceived women rights compared to men.

# Data Description
I am using EVS2018-GB.sav (EVS, 2020), the unit of analysis is ‘individuals’ in Great Britain. The sample size of the data set is 1788.
There are 181 variables (including 4 variables which have been recoded for this exercise and others) 

## Variable description 

1. Democracy

> **Variable Name:** democracy (variable 122)

**Variable label:** Political system: Having a democratic political system Level of Measurement: Ordinal

**Value Label:** (negative values are not used in the analysis) 

### Table 1

| Value | Label         |
|-------|---------------|
| 1     | Very Good     |
| 2     | Fairly Good   |
| 3     | Fairly Bad    |
| 4     | Very Bad      |

**Value Recoded:** Does not need recoding due to the variables already capturing the essential data points necessary to conduct a bivariate analysis.

2. Womens Rights

#### **Variable Name:** womenrights (variable 130)

**Variable Label:** Democracy: Women have the same rights as men. Is this a essential characteristic of democracy?

**Level of Measurement:** Ordinal

**Value Label:** (negative values are not used in the analysis, needs recoded see next section.)

### Table 2.1

| Value | Label                                                         | 
|-------|---------------------------------------------------------------|
| 0     | (It is against democracy 1 (spontaneous))                     | 
| 1     | (Not an essential characteristic of democracy)                | 
| 2     | 2                                                              | 
| 3     |  3                                                             | 
| 4     |  4                                                             | 
| 5     |  5                                                             | 
| 6     |  6                                                             | 
| 7     |  7                                                             | 
| 8     |  8                                                             | 
| 9     |   9                                                            | 
| 10    | (An essential characteristic of democracy)                    | 

**Value Recoded:** womenrights was recoded from 10 categories into 5 categories (Not essential, Somewhat essential,
Moderately essential, Very essential, An essential characteristic). This was done to give a more concise view of the answers, however not distilling it into too few categories which would lose nuance.

### Table 2.2

| Old Value | Label                                              | New Value | Label                                      |
|-------|---------------------------------------------------------------|-----|--------------------------------------------|
| 0     | (It is against democracy 1 (spontaneous))                     | 1   | Not essential                              |
| 1     | (Not an essential characteristic of democracy)                | 1   | Not essential                              |
| 2     | 2                                                              | 2   | Somewhat essential                        |
| 3     |  3                                                             | 2   | Somewhat essential                        |
| 4     |  4                                                             | 2   | Moderately essential                       |
| 5     |  5                                                             | 3   | Moderately essential                       |
| 6     |  6                                                             | 3   | Moderately essential                       |
| 7     |  7                                                             | 4   | Very essential                             |
| 8     |  8                                                             | 4   | Very essential                             |
| 9     |   9                                                            | 5   | An essential characteristic               |
| 10    | (An essential characteristic of democracy)                    | 5   | An essential characteristic of democracy   |


# Analysis

## Univariate Analysis

Conducted relevent univariate descriptive statistics, find more infromation in the markdown file [Univariate Analysis](#UnivariateAnalysis.md)

## Bivariate Analysis

Conducted relevent bivariate descriptive statistics, find more infromation in the markdown file [Bivariate Analysis](#BivariateAnalysis.md)

# Conclusion

> We are 99% confident that, in Great Britain, people who believe that they live in a very good democracy also believe that women rights are essential characteristic for a democracy.   

## References
EVS (2020). European Values Study Longitudinal Data File 1981-2008 (EVS 1981-2008). GESIS Data Archive, Cologne. ZA4804 Data file Version 3.1.0, [https://doi.org/10.4232/1.13486](https://doi.org/10.4232/1.13486).

## Copyright 
[european-values-survey-SPSS](https://github.com/ctmazilu/european-values-survey-SPSS.git) © 2024 by [Christina Mazilu](https://github.com/ctmazilu) is licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/) 
