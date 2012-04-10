---
layout: post
title: "Financial Tools"
date: 2004-02-18 20:43
comments: true
categories: MBA Finance
author: Oliver Thylmann
---


Here we consider a company as a conduit of funds. The higher the risk the higher the return required by investors and hence what the company must achieve. In terms of NPV (net present value), you should only do projects, as a company, that bring a positive NPV. The discount rate you use in your cost of capital, being the average return your equity and debt investors require. With a positive NPV, the project is adding value. It's that simple... ok, almost :)





**Determining the market cost of equity**

First you need to find the risk-free rate of return, which would be something that can be considered a safe investment. Treasury Bills are such a thing, which, given the credit-worthiness of most countries out there can be said to be relatively safe. Nominal interest rates will include an expected inflation and if the real one differs then investors will earn more or less in real terms, being an inflation risk.

For longer periods, government bonds could be taken, which have a given yield to maturity. Once your time horizon changes, you require different returns, called term structure of interest rates. 

Then you have the equity risk premium. The equity rate of return could be said to be the rate of return of the stock market, which you can invest in via an index or tracker fund (highly suggested if you are thinking about investing mind you). The difference between the equity rate of return and the risk free rate is the equity risk premium. In the last 100 years or so, this can be said to have been between 5.6% and 6.6%, on average. As both risk free rate and return on equity are influenced by inflation, the premium should be constant. 

**Determining the individual cost of equity**

This can be shown to depend on the return of the share in relation to the market. Harry Markowitz developed the portfolio theory in relation to this, or more clearly, in relation to the benefit that can be gained by combining shares into a portfolio. Several assumptions need to be made here though:
- all investment decisions are made within a single period framework (one time frame)
- more money is preferred to less money
- investors are risk-averse, and hence need an extra return for extra risk
- attraction of shares are measured only by their expected returns and standard deviations (the biggest flaw in the model I'd say and mind you it's a damn good one)

In the end, the risk of an All-Share portfolio is less than the average one of an individual share. The calculations have been seen previously. In general, it's about shares now being 100% correlated in their movements, meaning if one share goes up, another one goes down, and the risk attached to the movedment of them both together is lower than of each one of them. If they have only a small correlation coefficient that is. The correlations coefficient is the covariance (extent to which the shares move together) divided by standard deviation of returns for the shares your are mixing. The value will be between -1 and +1. The lower the correlation, the greater the risk reduction. 

Combining shares intelligently, will allow your to lower your risk while not sacrificing return. The set of all portfolios you can take is known as the opportunity set and the edge of that set, in terms of risk and return, is known as the efficient frontier. Efficient as it offers the maximum expected return for the related risk. Optimisation is the mathematical process to maximize return for risk. Even simply picking a few shares, called naive diversification, reduces risk ,as it does not need many shares to reduce the risk considerably. 10 shares give you a risk of only 70% in relation to one share. The more shares you hold the closer your portfolio is like the stock market and you approach both market return and market risk.

The capital asset pricing model (capm) adds to the portfolio theory that a) there is a risk-free asset for all investors and b) that all investors have the same expectations as for the future, meaning that they accept the forecasts made. This also means that everybody would everybody invests in the same portolio of shares, being called M at this time. If you draw a straight line from the risk-free asset (Rf) touching the efficient frontier at M, you get the capital market line. You can now choose your risk and return via buying different distributions of Rf and M, moving your risk/return along the line. 

E(Rp) = ÃŸE(Rm) + (1-ÃŸ)Rf = Rf + ÃŸ[E(Rm) - Rf]

For ÃŸ=0 you get the risk free rate. For ÃŸ=1 you get the market portfolio. For ÃŸ&gt;1 you borrow (ÃŸ-1) and invest that in the market.

All in all capm means that you only invest in an index fund and a risk free asset, which is actually rather wise. The other solution would be to believe that different people have different expectations in shares/companies and therefore over or undervalue shares. This is fine on its own, but the problem is that you will also have to be sure that your expectations are &quot;correcter&quot; than the market average. 

The security market line can also be drawn, being:

E(Ri) = Rf + ÃŸi[E(Rm) - Rf] where ÃŸi is the beta of the share i (correlation to the return of the stock market).

This security market line implies that the required return for individual shares does not depend on the total risk but just on the risk relative to the market. You therefore can express the exptected return per share via the risk-free rate, the equity risk premium and the share's beta. You can get betas from most stock web sites out there.

Another thing of importance then becomes the alpha, which measures the performance in relation to the security market line. You will then see that the total risk of a share is made up of the beta, market risk and specific risk of the share. As the theory goes, the specific risk will be cancelled out in a diversified portfolio and you then can use the CAPM model.

The next model would be the divident valuation model. This defines the price P of a share as the present value of future dividends, discounted by the RRR. 

P = Sum over ( D_1 / ((1+E(R))^n))

The problem here is that you do not know wha the dividends will be and often companies in high growth do not give out dividends in the arguement that the money is better reinvested in the business.

The simplified version of this is the *Gordon growth model*, which presumes that you have a constant growth g:

P = D_1 / (E(R) - g)

You can turn this arround to get the RRR for a share taking its dividends as a measurement:

E(R) = (D/P) +g

To find the growth in dividends, take a look at forecasted real growth and expected inflation. This way you can compare across boundaries and allows you to compare the CoE of the Gordon growth model with your result from CAPM. 

**Capital Structure and WACC**

The two main types of finance, dept and equity, make up the capital structure of a company. Debt is normally taken as risk free, even though it isn't. Credit ratings show the danger attributed to the debt resulting in different interest payable on debt. As the risk free rate Treasury Bill yield or LIBOR (London Interbank Offered Rate) is often taken, even though companies with very low risk rating can potentially borrow at below LIBOR. 

To determine the future cost of dept one approach is to take historic cost or to take an average x points above risk free.

This brings us to capital structure. The main ratios here are gearing, net gearing, leverage (gross), leverage (tangible), leverage (tangible including contingents) and debt/debt plus equity (dept/equity for short). 

Debt/equity ratio = (short- and long-term debt)/(short- and long-term debt + shareholders' equity)

The more commitment there is to pay for debt via cash flows, the more volatile the remaining profits distributable to shareholders will be. A high gearing therefore leads to a higher required return for shareholders. If we introduce corporate tax, with tax-deductible debt interest payments, then the true cost of debt actually lower. This results in a company with debt potentially being worth more than one without. 

This would speak for a high gearing, with the only problem being that first of all you need enough profits to show against interest payments and there is the problem of bankrupty if you fail to pay your interest. The more likely a default, the higher the interest rates on debt. You need to weight all of this against each other to have the optimal debt/equity ratio.

Next up comes the weighted average cost of capital (WACC)

R = D/(D+E) x R(debt) (1-T) x E/(D+E) x R(equity)

Here you should use market prices for equity (E) and debt (D). You can also use your long-term debt to equity target ratio in the calculation. Increasing debt/equity ratio reduces the WACC. Sometimes companies use a hurdle rate higher than their WACC in project appraisal. Explanations might be:
- counter over-optimism
- to compensate for negative NPV projects that had to be done
- to factor in options (e.g. not delaying the project a year if possible)
- interest rates change
- riskier projects

Adjustments should be made to the hurdle rate in case there are special risks involved, be they operational risks or financial risks. For operating risk you could for example change the beta of the business that will undertake the project in relation to the market. Also take into account currency and political risks in international businesses. In terms of financial risks, look at asset and equity betas. 

ÃŸ(asset) = D/(D+E) x ÃŸ(debt)x(1-T) + E/(D+E) x ÃŸ(equity)

**Dividend policy**

Here managers can again influence the financing structure of the company. The first idea is that a dividend today is worth more than a potential gain in the future (tell that to Microsoft though ;)). In the early days, investors only looked at dividends but in 1959 dividend yields dipped below bond yields, showing that investors started looking at capital gains too.

The problem with the argument that higher dividends should result in higher stock price, is that a higher dividend does not really have an impact on the business risk of a company. In light of taxes there is a change in the equity structure of a business though due to dividend payments. There is actually a tax disadvantage due to the fact that dividends are taxes first through corporation tax and then by the shareholder as income tax.

In this game though it is important to know that taxes play a big role and this also means that it might change from time to time if it is wise to pay dividends or not. 

In terms of agency theory, it can be argued that management might use dividend payments to make belief that they are acting in the interest of the shareholders. Also shareholders might like to drain the company of a bit of cash to have management go to standard markets for debt, giving their projects a mor thorough look.

Signalling theory by Miller and Modigliani (1961) suggest that dividends are used to convey information about future earnings. Management cannot pass out certain information and this is how they could in a secret way.


