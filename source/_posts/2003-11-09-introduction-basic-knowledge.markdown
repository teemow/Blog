---
layout: post
title: "Introduction - Basic Knowledge"
date: 2003-11-09 19:43
comments: true
categories: OUBS
author: Oliver Thylmann
---


&lt;p&gt;(comment: As originally posted on the [OUBS Blog](http://blog.thylmann.net/category/oubs/))
[The course](http://www3.open.ac.uk/oubs/bin/oubs.dll?CB821) has started. The course starts with an introduction book, something I will cover shortly here. Most of the things will be common knowledge but I will add the most important functions here for later reference.&lt;/p&gt;

&lt;p&gt;I'll start with the second chapter (Algebra, graphs and calculus). Here are some basics:&lt;/p&gt;

&lt;p&gt;a&lt;em&gt;0 = 0
a&lt;/em&gt;1 = a
a + b = b + a
a&lt;em&gt;b = b&lt;/em&gt;a
a&lt;em&gt;(b+c) = a&lt;/em&gt;b + a&lt;em&gt;c
a+(b+c) = (a+b)+c
a&lt;/em&gt;(b&lt;em&gt;c) = (a&lt;/em&gt;b)*c&lt;/p&gt;

&lt;p&gt;Moving on to solving equations, one thing can be said: whatever you do on one side of an equation, you do on the other too (like adding 2 or multiplying x), then you are just fine. You should also take the unknown to one side of the equation. All in all, always follow that system. Multiply, add, substract, remove brackets, whatever, just get the unknown on one side so that the result is something like X = 2. It might takesome time but you'll get there. If you have two variables, just take one of them on one side and the other on the other side.&lt;/p&gt;

&lt;p&gt;Next on our list are logarithms. For me, these buggers are hard to wrap my head arround. Somehow, x*y seems fully natural but log(x) doesn't, while it should. So here are some rules:&lt;/p&gt;

&lt;p&gt;Log (xy) = Log x + Log y
Log (x/y) = Log x - Log y
Log (x^n) = n Log x
Log (x^(1/n)) = (1/n) Log x
Log (x^-n) = -n Log x&lt;/p&gt;

&lt;p&gt;The same can be done for natural logarithms, which are written &quot;ln&quot; and are in relation to powers based on &quot;e&quot;. Never mind what it all means, just that &quot;e&quot; is, as weird as it sounds, a very special number that will come up in lots of cases.&lt;/p&gt;

&lt;p&gt;Next the book looks at graphs and how to find the function behind them. In general, the folloing terms are useful:&lt;/p&gt;

&lt;p&gt;Rise / Run = y height climed / x distance travelled = change in y value / change in x value = slope. This is probably more interesting to somebody without english as his native language, like me ;)&lt;/p&gt;

&lt;p&gt;Now this slope brings us to the first derivative though, because the first derivative is the slope of a graph. In a sense it is:&lt;/p&gt;

&lt;p&gt;Change in y / Change in x&lt;/p&gt;

&lt;p&gt;When we go into minute changes in both x and y, then we are doing a differentiation. Here we need some rules which I still remember all too well from physics studies.&lt;/p&gt;

&lt;p&gt;dy/dx = na x^(n-1) is the differentiation of y = ax^n&lt;/p&gt;

&lt;p&gt;Implied in this is that you will have a low or highpoint in a graph if the differentiation is 0. A high point would be present if the second derivative is negative (the y values going down with increasing x values after the point), a lot point if it is positive (y going up). Remember that you can also do partial differentiation, meaning that you differentiate only for one variable.&lt;/p&gt;

&lt;p&gt;&lt;strong&gt;Statistical techniques&lt;/strong&gt; is next. Everything starts with averages and here you have three:
- The arithmetic mean, being the sum of all values devided by the number of values. That the average evryone knows.
- The mode is the data that occurs most frequently
- The median is the middle data, when all data is arranged in order of magnitude.&lt;/p&gt;

&lt;p&gt;You can calculate all three with Excel or other spreadsheets. Another mean is the geometric mean which is calculated my multiplying the different values and taking the nth root of the product. This is used when there is some kind of compounding in the data series.&lt;/p&gt;

&lt;p&gt;Another important item in statistics is teh range = x(max) - x(min). It will help us find the spread of data arround the middle. Here the standard deviation is useful.&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;238&quot; height=&quot;72&quot; border=&quot;0&quot; alt=&quot;standard_deviation.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/standard_deviation.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;The variance is the square of the standard deviation (V = S^2)&lt;/p&gt;

&lt;p&gt;Next up is the normal distribution, which is kind of the shape of the data or graph in question. The normal distribution is the typical bell shape. For any normal distribution there are a few facts:
- 68.26% of readings occure within +/- 1S
- 95.45% within +/- 2S
- 99.74% within +/- 3S&lt;/p&gt;

&lt;p&gt;In general, a sample of n&gt;30 will suffice to use standard deviation. The sample mean will possibly be a number of standard errors arround the true population mean, but due to being normally distributed, 95% will be within +/- 1.96 SE and 99% within +/- 2.58 SE, where SE = (population standard deviation) / (route of sample size). Therefore, if we want to find the range of true means within the population with a 99% certainty, then we need to calculate the sample size mean +/- 1,96SE.&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;153&quot; height=&quot;70&quot; border=&quot;0&quot; alt=&quot;sample_to_population.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/sample_to_population.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;Next up, &lt;strong&gt;correlation and covariance&lt;/strong&gt;. We can have positive or negative correlation in relation to whether one variable reacts the same way or adverse to another variable. Correlation analysis is done to find links between different sets of data. A first thing to do this is to draw a scatter diagram, simply putting all your data points into a chart and then seeing if they have something in common. The correlation formula is the following:&lt;/p&gt;

&lt;p&gt;[&lt;img width=&quot;350&quot; height=&quot;60&quot; border=&quot;0&quot; alt=&quot;correlation.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/correlation-thumb.jpg&quot; /&gt;](http://owt.typepad.com/oubs/images/correlation.jpg)&lt;/p&gt;

&lt;p&gt;Regression analysis is used to find a relationship between two sets of data. If you estimate within your range of data you are doing an interpolation, where an extrapolation would be about making estimates for values outside your observed range.&lt;/p&gt;

&lt;p&gt;In general, you will find the following:&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;274&quot; height=&quot;135&quot; border=&quot;0&quot; alt=&quot;linear_regression_analysis.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/linear_regression_analysis.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;This part of the book finishes off with time series analysis. Here you take, for example, your quarterly data, add 4 quarters up, device them by 4 and you get your 4-quarter moving average. Averaging two 4-quarter moving averages will give you the centered 4-quarter moving average, allowing you to compare this average with the real value, giving you seasonal variation. Then you can forecast sales and take into account seasonable variations.&lt;/p&gt;


