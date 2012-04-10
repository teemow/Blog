---
layout: post
title: "Introduction - Cost of Finance"
date: 2003-11-23 20:05
comments: true
categories: OUBS
author: Oliver Thylmann
---


&lt;p&gt;(comment: As originally posted on the [OUBS Blog](http://blog.thylmann.net/category/oubs/))&lt;/p&gt;

&lt;p&gt;Here we look at portfolio theory, the capital asset pricing model (CAPM) and the dividend valuation model.&lt;/p&gt;

&lt;ol&gt;
&lt;li&gt;Portfolio Theory&lt;/li&gt;
&lt;/ol&gt;

&lt;p&gt;In general, the annual percentage return of a stock is calculated by:&lt;/p&gt;

&lt;p&gt;The risk is calculated by looking at the variations of returns over several periods, which is the standard deviation of the measurements. Portfolio theory states that a mix of several investments will hold a smaller risk than their mean or weighted average risk. This is due to the less than perfect correlation between the movements in value of both investments. In case of stock A and B, they will fluctuate less in value together as one might go up while the other goes down or even only less up. The risk is calculated via the portfolio equation:&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;375&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;80&quot; border=&quot;0&quot; alt=&quot;Portfolio Equation&quot; src=&quot;http://owt.typepad.com/oubs/images/portfolio_equation.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;To look at the portfolio with the least risk you employ some mathematical wizardry. First you find that W(y) = 1 - W(x) and replace W(y) with the right side of that equation. Then you differentiate the Portfolio Equation with respect to W(x) and then equate that to 0. When you solve that equation, you will have a turning point in the slope of the equation. This gives us:&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;343&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;57&quot; border=&quot;0&quot; alt=&quot;Minimal Risk&quot; src=&quot;http://owt.typepad.com/oubs/images/minimal_risk.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;where Var(R(p)) = S(p)^2&lt;/p&gt;

&lt;p&gt;In a multi-asset portfolio the entire formula becomes:&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;276&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;73&quot; border=&quot;0&quot; alt=&quot;Multi-Asset Portfolio&quot; src=&quot;http://owt.typepad.com/oubs/images/multi-asset_portfolio.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;If you would plot a graph with your different potential mixes of investments, you will find that there is an opportunity set of investments and this graph has something called the efficient frontier. This is where there is the least risk for the chosen return. We can use that graph to find the optimal mix of a risk free investment and a mix of stocks by putting the tangent on the efficient frontier and then choosing a mix of the touching point and the risk free investment that will give us our wanted risk. This line is the capital market line.&lt;/p&gt;

&lt;p&gt;This allows us to easily find a portfolio mixing risk-free investments and a given portfolio with a given risk ( m stands for shares and f for the risk-free asset).&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;304&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;45&quot; border=&quot;0&quot; alt=&quot;Expected Portfolio Return&quot; src=&quot;http://owt.typepad.com/oubs/images/expected_portfolio_return.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;Here we have been considering a market portfolio against a risk-free investment. This entire system can also be used to analyse individual shares in relation to the market portfolio (CAPM). Here we find two things. First of all, the beta of the share, meaning the fluctuation of the shares against the flucuation of the market portfolio. With the help of that we can find out what the risk of the share is in relation to the market risk taking into account the risk free investment.&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;265&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;113&quot; border=&quot;0&quot; alt=&quot;beta&quot; src=&quot;http://owt.typepad.com/oubs/images/beta.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;Another item that is important when investing in stocks are the dividends. One way to value them is to simply discount them to get their current value. The other method is the &lt;strong&gt;Gordon growth model&lt;/strong&gt;, which can be used if the dividends are growing by a constant percentage each year.&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;176&quot; height=&quot;67&quot; border=&quot;0&quot; alt=&quot;gordon_growth_model.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/gordon_growth_model.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;Where P is the price of the shares, D(1) the dividend after one year, E the expected rate of return and g the growth rate of the dividend.&lt;/p&gt;

&lt;p&gt;Next stop: &lt;strong&gt;Bonds&lt;/strong&gt;, starting with some definitions:
- basic coupon yield or current yield: is only about the coupon rate / price
- coupon rate: fixed interest rate as a percentage of par (or nominal or face value)
- par, nominal or face value: the quoted value independent of the current market value of the bond
- adjusted coupon yield: recognizes any redemption payment, apportioned in a straight-line basis
- yield to maturity: IRR of the bond&lt;/p&gt;

&lt;p&gt;Another item is the duration of bonds, which is the accumulated present value of cash flows occuring at each time period of the bond.&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;197&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;77&quot; border=&quot;0&quot; alt=&quot;Duration of Bonds&quot; src=&quot;http://owt.typepad.com/oubs/images/duration.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;Moving stuff around in this equation we get this:&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;219&quot; vspace=&quot;0&quot; hspace=&quot;0&quot; height=&quot;74&quot; border=&quot;0&quot; alt=&quot;Duration of Bonds&quot; src=&quot;http://owt.typepad.com/oubs/images/duration2.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;The duration is always less than the maturity, unless it is a zero coupon bond. This duration presumes that as the yield of the bond changes, the price changes too, and that this is happening in a straight line method, which is just not true, something that is known as the convexity of bonds. The convexity of the bond is always to the benefit of the shareholder and a more convex bond is more attractive. This is a highly complicated subject, further reading on the subject of bonds, with great detail, can be found [here](http://investopedia.com/university/advancedbond/).&lt;/p&gt;

&lt;p&gt;&lt;strong&gt;WACC&lt;/strong&gt; stands for &quot;weighted average cost of capital&quot;, which is used to find a value to discount against in the NPV model. It's calculated as follows:&lt;/p&gt;

&lt;p&gt;WACC = (Dept / (Dept + Equity))&lt;em&gt;(Cost of Dept)(1 - Corporate tax rate) + (Equity / (Dept + Equity))&lt;/em&gt;Cost of equity&lt;/p&gt;

&lt;p&gt;When working with foreign exchange, you need to remember that traders will sell foreign exchange at a lower rate than they will buy it, which is called their spread. They will sell low and buy high. There is an interesting spread sheet included on page 151 showing how to go about calculating your sell and buy rates. Then there is also the forward exchange rate, which is an agreement for delivering e.g. $X for â‚¬Y at a future date. These will be quoted in two ways being: forward outright = spot + forward margin&lt;/p&gt;

&lt;p&gt;Then there is also a connection between exchange rates, interest rates and inflaction rates summaries as follows.&lt;/p&gt;

&lt;p&gt;Purchasing power parity (PPP): (1+ UK expected inflation) / (1+USA expected inflation) = (USD/GBP spot) / (USD/GBP forward)&lt;/p&gt;

&lt;p&gt;The fisher effect: (1 + nominal rate) = (1+ real rate) (1+expected inflation rate)&lt;/p&gt;

&lt;p&gt;Interest rate partiy theory: (1+UK interest rate) / (1+US interest rate) = (USD/GBP spot) / (USD/GBP forward)
This will be further covered in unit 8, which will explain that market forces will maintain this ballance.&lt;/p&gt;

&lt;p&gt;Options are also covered at the end of the section, including black-scholes and other theories, but they are only touched upon and I will not put this here.&lt;/p&gt;



