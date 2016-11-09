##scikit-learn
* 1.1.2 Ridge Regression¶
$$
\min \limits_{x} \left\|Xw-y \right\|_2^2+ \alpha \left\|w \right\|_2^2
$$
\>>>from sklearn import linear_model
\>>>reg = linear_model.Ridge (alpha = .5)

* 1.1.3 Lasso (*Least Absolute Shrinkage and Selection Operator*)
$$
\min \limits_{x} \left\|Xw-y \right\|_2^2+ \alpha \left\|w \right\|_1
$$
\>>> from sklearn import linear_model
\>>> reg = linear_model.Lasso(alpha = 0.1)

== from sklearn.metrics import r2_score==
$$1-\frac{\sum(y_i-\hat{y}_i)^2}{\sum (y_i-\overline{y})^2}$$
