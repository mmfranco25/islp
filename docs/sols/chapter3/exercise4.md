
# Exercise 3.4

(a) <b>Cubic regression will have lower Residual Sum of Squares (RSS).</b> The cubic regression model is more flexible than the linear regression model. Accordingly, the cubic regression model can fit the data better and achieve a lower training RSS than the linear regression model.

(b) <b>Linear regression will have lower RSS. </b> In general, more flexible models have less bias and higher variance. By contrast, more rigid models have high bias and lower variance. Since it is said that true relationship between the predictor and the response is linear, we know that, in this case, the linear regression model will have low bias. Consequently, this model will perform better than the cubic regression model, which is expected to have higher variance. 

(c) <b> Cubic regression will have lower RSS. </b> Same reason as in (a). Since the model is more flexible, it is able to fit the data better.

(d) <b>Not enough information to tell.</b> Due to its flexibility, it is generally expected that the cubic regression model has lower bias and higher variance than the linear regression model. In this exercise, we know that the true relationship is non-linear, but we don't know how far it is from linear. This means that we don't have any idea about how high the bias of the linear regression model can be. If the model is just slightly non-linear, the linear regression will be able to model the data and achieve low bias. Thus, we would expect the linear model to have low bias and low variance. This could be enough (or not) to beat the cubic regression model, which is expected to have low bias and high variance. However, if the true relationship is substantially non-linear, the linear model will not be able to model the data and its bias will be high. With high bias and low variance, the linear regression model is beaten by a cubic model without [overfitting](https://youtu.be/DQWI1kvmwRg) problems. It will always depend on the bias-variance trade-off and, in general, on the size of the training set and the magnitude of the noise. We would need more information to know which model would have lower RSS.