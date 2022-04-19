---
title: "Missing Data"
icon: "ti-search"
description: "What is the nature of missing data? How to consider handling missing data?"
type: "docs"
---

Handling **missing values** can be a component of data pre-processing as well as feature engineering. Missing values can occur for several reasons including structural deficiencies in the data (namely, deliberate omission in the data collection or data generating process), random occurrences, or specific reasons.  

A structural deficiency would be the case of a missing component of a predictor omitted from the data. Typically, these cases could be resolved once the necessary component is identified. For example, if a hypothetical dataset has some predictor variable where values are either “A” or “B” or missing, where most values are missing, it may be tempting to discard the predictor variable due to the high rate of missingness. However, discarding this predictor variable may inadvertently be throwing away valuable information since missing can be interpreted to mean not being “A” or “B”. A better recording of the predictor variable may be to replace the missing values with “Not A or B”.  

Another reason for missing values may be due to random occurrences. This can be occurrences missing completely at random (“MCAR”) where the likelihood of a missing value is equal for all data points, both observed and unobserved. Missing values can be interpreted here as independent of the data generating process.  This can also be an occurrence missing at random (“MAR”) where the likelihood of a missing value is not equal for all data points. In this case, the probability of a missing value depends on the observed data, but not unobserved data. 

A third reason for missingness can be due to specific reasons or missing not at random (“MNAR”). This often occurs in cross-sectional time series data where the same unit of observation (for example, patient in medical trial) drops out of a study. Measurements for this unit of observation will stop after dropping out of the study. The MNAR cases are difficult to handle in practice and data practitioners should seek to understand the nature of the missingness before applying a technique to correct for missingness since a misdiagnosis of missingness could lead to bias in model inference.  

**Attribution:** 

Johnson, K. and Max Kuhn. (2019, June 21). <i>Feature engineering and selection: A practical approach for predictive models.</i> Feature Engineering and Selection: A Practical Approach for Predictive Models. Retrieved from <u>http://www.feat.engineering/</u>