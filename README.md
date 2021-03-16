# Women Who Exercise
## Exploratory Data Analysis

### Introduction
This project used exploratory data analysis techniques in Python to prove or disprove a hypothesis based on female exercise behavior with those who have kids under the age of 18 based on a survey of time usage. 

### Hypothesis
Women who have children under the age of 18 exercise less than women who do not have children under the age of 18.

### Data
American time Use Survey: https://www.kaggle.com/bls/american-time-use-survey

### Techniques

* Histograms
* Scatter plots
* Descriptive statistics
* Outlier detection
* Probability mass function
* Cumulative distribution function
* Correlation
* Permutation test
* Regression

### Outcome
Looking at if females who have children exercise less than those that do not have children, through comparisons of CDF, hypothesis testing, and simple regression, the analysis points to the null hypothesis being statically significant. The null hypothesis will be rejected and will accept the alternative that females with children exercise less than those that do not have children. Comparing the two CDF’s of the groups and their exercise durations, women who do not have children had an overall higher probability of exercising longer. There were exercise durations that the two had the same CDF, at 30 minutes and 60 minutes. Through regression, having children alone does not account for the majority of reasons why females exercise less. Having children only accounts for 0.9% of the difference in exercising between the two groups. Other reasons as to why they exercise less were not found in this study. When adding other variables such as age, hours the respondent worked, and the hours their spouse worked, it increased the accountability for exercise duration to 4.1%. However, having children or no children did not affect the duration of exercise when mixed with the other variables. In this case, the null hypothesis would be accepted and the alternative would be rejected. There are many other reasons for women’s exercise habits that were not discovered. 

#### Note
This analysis utilizes supported code from Allen Downey's ThinkStats2 https://github.com/AllenDowney/ThinkStats2
