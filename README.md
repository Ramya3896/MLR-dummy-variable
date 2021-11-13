## MLR-dummy-variable-trap
This is a hands on of fitting a multiple linear regression with a discovery of a dummy variable trap in the process.

### How OneHotEncoder method gives rise to multi collinearity problem?
* Understanding OneHotEncoding! 

OneHotEncoder method by default transform the categorical variable into a vector of binary variables resulting in multicollinearity. Because one column of vector perfectly correlated with other as it is a compliment of other columns of transformed vector. 

Thus we shall remove one column of transformed vector to avoid dummy variable trap. 

Why a multi-collinearity a serious problem?
Multi-collinearity seriously affects the estimated coefficients of the model. 

