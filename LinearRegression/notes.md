Multicollinearity - The presence of high correlation among the independent variables in a regression model.
when the independent variables are highly correlated, becomes difficult to dtermine the individual effect of each variable in the output

Multicollinearity can lead to high standard errors making it difficult to say the variable is siginficant or not.

when Multicollinearity occurs, the p value of the variables is usually high, and the confidence intervals are wide.

Multicollinearity can be detected using the correlation matrix which is very best suitable for the pairwise correlations.
, the other method is the VIF which is known as the variance inflation factor, the VIF will be able to explain the correlation between the more than two variables.

VIF = 1 / (1 - R^2)
where R^2 is the coefficient of determination of the regression model with the independent variable of interest as the dependent variable and all other independent variables as predictors.
VIF > 10 indicates high multicollinearity, and VIF < 5 indicates low multicollinearity.

Perfect multicollinearity exist when two variables have the correlation coefficient of exactly 1 or -1, making hars to find the regression line