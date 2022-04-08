---
title: "Feature Engineering"
icon: "ti-search"
description: "What is feature engineering and considerations in performing feature engineering"
type: "docs"
---

**Feature engineering** is related to data pre-processing but is more closely related to the modeling process. Feature engineering refers to when model inputs or features are generated that are then incorporated into a model for training. Typically, this means adjusting and reworking the predictors to enable models to better uncover predictor-response relationships. The <i>engineering</i> involves the steps taken to improve model performance by generating the appropriate features. Since we may not know in advance what adjustments or re-adjustments of the features are required to improve model performance, the re-working of predictors can be experimental in nature requiring experience and tools to find predictor representations. 

Feature engineering can involve scaling (to scale numerical features so that they are in the same numerical scale) through standardization or normalization. Normalization involves mean scaling where the mean value of a particular feature is subtracted from each feature value. Standardization involves variance scaling where each feature has a mean value of zero and standard deviation of one.  

If a feature can take on many values, it can be normalized with buckets. For example, if a feature is real-valued, ordinal, or integer valued, the values can be arranged into several different buckets. In some cases, features can be encoded into binary values (0 or 1, “Yes” or “No”, null or not null). The latter is typically the case with text features. 

**Attribution:** 

Johnson, K. and Max Kuhn. (2019, June 21). <i>Feature engineering and selection: A practical approach for predictive models.</i> Feature Engineering and Selection: A Practical Approach for Predictive Models. Retrieved from <u>http://www.feat.engineering/</u>