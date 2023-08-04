## Normality
Check if the normalidade of the residous is normal. It does not garantee that multivariate normality holds but it's a great indicator.
For that we can use statistical tests like Shapiro-Wilk or Kolmogorov-Smirnov

## Homoscedasticity
Does the variance of the dependent variable follows the variance of the indepent variable? If thats not true we can have problems with model performance.
Multicollinearity is also a relevant aspect. 
For this check we can use Levene or the Breusch-Pagan test.

## Linearity
Non linear data can harm the model but they are less harmful then lack of indepence between features and non homogeneity of residuals
