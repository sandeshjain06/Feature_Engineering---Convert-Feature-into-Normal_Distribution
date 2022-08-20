# Feature_Engineering  -  Convert Feature into Normal_Distribution


Feature Transformation
Transforming the features distribution into normal distribution

Most algorithm requires the feature into normal distibution while some does not requires that such as decision tree , random forest, here it does not matter whether the feature distribution is normal or not.

Linear and logistic regression requires the data in normal distribution.

How to check feature is normal or not.
sns.distplot()

Check the skewness - if pd.skew() = 0 , then normal else skewed.

QQ plot - Reliable way to check whether feature is normal or not.

Below we have draw the qq plot if line is straight then it is normal else skewed

Types of Feature Transformation
Log Transform : If data is right skewed data then use it.

Reciprocal Transform :

Power Transform - square , square root : If data is left skewed data then go with square power transform.

Box-Cox Transform

Yeo-Johnson Transform.

Function Tranformer
Log Transform
Reciprocal Transform
Power Transform - square , square root
Custom Transformer
Power Transform
Box-Cox Transform : 1. values > 0 , 2.values cannot be negative.
Yeo-Johnson Transform : Overcome problem of box-cox transform.
