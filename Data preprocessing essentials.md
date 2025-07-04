## What is Data Preprocessing?
The process of transforming raw data into a clean and usable format for machine learning algorithms.
<!--ID: 1751647047346-->


## Steps in Data Preprocessing
### Normalization: 
Bringing Values to a Common Scale
It prevents features with larger values from dominating those with smaller values, improving model convergence & accuracy. This is applied to the numerical values column.
The common method we use is called Min-Max Scaling.
*The formula is*
x_ normalized = (x-min(x)) / (max(x)-min(x))
<!--ID: 1751647047430-->


*Use Cases of Normalization*
Ideal when the distribution of your data does not follow a Gaussian distribution.

### Standard Scaling(Standardization)
Transform features to have a mean of 0 & a standard deviation of 1.
This is also applied to numerical values column.
This is applied to make features comparable across different scales & distributions, improving model stability & performance.
*Common Method* : Z-score Scaling
*Formula is*: 
x_scaled = (x - mean(x)) / standard_deviation(x)
<!--ID: 1751647047439-->


*Use Cases of Standard Scaling*
Often used when your data follows a Gaussian distribution or when algorithms assume a normal distribution (e.g., linear regression, logistic regression)

###  One-Hot Encoding
This technique is applied Categorical column.
It transforms Categorical features into numerical format for machine learning models.
It is used because many algorithms cannot directly handle Categorical data.
*How*
Create a binary column for each unique category value, with a 1 indicating the presence of that category for a particular data point.
<!--ID: 1751647047447-->

