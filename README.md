# LRMisconceptation

## Misconceptations on Using Linear Regression

"The scatter plots of <b><i>y ~ x<sub>i</sub></i></b> don't look linear to me. Let's use then Random Forest or Neural Network". Reality is that linear regression still is the workhorse of Machine Learning despite several misconceptations regarding its applicability. 

## What Should be <i>Linear</i> in <i>Linear</i> Regressions?

Linear refers to the relationship between the parameters that you are estimating (e.g., β) and the outcome (e.g., y). Hence, <b><i>y=e<sup>x</sup>β+ϵ</i></b> is linear, but <b><i>y=e<sup>β</sup>x+ϵ</i></b> is not. A linear model means that your estimate of your parameter vector can be written β&#770=∑iwiyi, where the {wi} are weights determined by your estimation procedure. Linear models can be solved algebraically in closed form, while many non-linear models need to be solved by numerical maximization using a computer.

### Reference Websites

[Real-Time Time Series Anomaly Detection](https://towardsdatascience.com/real-time-time-series-anomaly-detection-981cf1e1ca13)
