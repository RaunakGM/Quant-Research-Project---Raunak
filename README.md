QUANT RESEARCH PROJECT

PROBLEM SOLVING EXPLANATION:

1.	Z-SCORE BASED TRADING SYSTEM (BASE MODEL)-
   
The aim is to capture deviations from the mean of the time series. Z-score measures the deviation of a particular observation from the series’ mean in terms of standard deviations.
After calculating the z-score for all the observations we can study the data and identify deviations from the mean which can be a good opportunity of pair trading.
Pair trading can be done by selling the overvalued index and buying the undervalued index.

2.	REGRESSION:
   
Regression involves developing a relationship between a dependable and non-dependable variable. The relationship if linear can be expressed using the straight line equation (y=mx+c),
where m is the slope of the line, which can be referred to as hedge ratio here. Using the relationship we can predict the values of bank nifty.  After predicting bank nifty values,
we can subtract this from the real bank nifty values which form the spread. We can again use z-score to determine the extent of the deviation and generate trading signals.
OLS regression can also be used for this process. This type of a regression uses ordinary least square function to minimize the errors.

3.	RATIO METHOD:
   
This method involves dividing bank nifty by nifty, to obtain ratios which can help us measure deviations from the normal trend. Very high or very low ratios suggest deviations from the mean.
Z-score of these ratios can be useful in determining the extent of deviation.
