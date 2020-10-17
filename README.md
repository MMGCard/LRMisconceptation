# LRMisconceptation

## Misconceptations on Using Linear Regression

"The scatter plots of y ~ x<sub>i</sub> don't look linear to me. Let's use then Random Forest or Neural Network". Reality is that linear regression still is the work horse of Machine Learning despite several misconceptations regarding its applicability. 

h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x

## What Should be Linear in Linear Regressions?

Linear refers to the relationship between the parameters that you are estimating (e.g., β) and the outcome (e.g., y). Hence, y=e<sup>x</sup>β+ϵ is linear, but y=eβx+ϵ is not. A linear model means that your estimate of your parameter vector can be written β^=∑iwiyi, where the {wi} are weights determined by your estimation procedure. Linear models can be solved algebraically in closed form, while many non-linear models need to be solved by numerical maximization using a computer.

### Reference Websites

[Real-Time Time Series Anomaly Detection](https://towardsdatascience.com/real-time-time-series-anomaly-detection-981cf1e1ca13)
