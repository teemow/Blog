---
layout: post
title: "Introduction - Application to financial techniques"
date: 2003-11-09 19:44
comments: true
categories: OUBS
author: Oliver Thylmann
---


&lt;p&gt;(comment: As originally posted on the [OUBS Blog](http://blog.thylmann.net/category/oubs/))
This is where it gets a lot more interesting. We are looking at investment appraisal.&lt;/p&gt;

&lt;ol&gt;
&lt;li&gt;The time value of money&lt;/li&gt;
&lt;/ol&gt;

&lt;p&gt;This is about compounding and discounting, meaning that money is worth less in the future and this more is also dependant on interest on interest gained. The compounding formula is the following:&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;174&quot; height=&quot;57&quot; border=&quot;0&quot; alt=&quot;compounding.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/compounding.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;where S is the sum owing after the time t on the principal P with an interest x. If you turn the formula arround, calculating P based on S, you can find out the present value of money that you will receive in the future: the present value or the discounted value. $1 received in a year, is only worth $0.9091 in case we take an interest rate of 10%. The discount factor would for money received in a year at 10% interest would then be 0.9091.&lt;/p&gt;

&lt;p&gt;What about receiving payments in a regular manner. Here we need the formula for payment value of an annuity. (r = 1+x/100))&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;206&quot; height=&quot;68&quot; border=&quot;0&quot; alt=&quot;annuity.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/annuity.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;If we want to get $1000 per year for 10 years and our interest rate is 10% then we get $6144 as the money to be put into the account at the beginning of the period. We can turn this arround to calculate annual repayment sums, for mortgages for example.&lt;/p&gt;

&lt;p&gt;&lt;img width=&quot;217&quot; height=&quot;70&quot; border=&quot;0&quot; alt=&quot;mortgage.jpg&quot; src=&quot;http://owt.typepad.com/oubs/images/mortgage.jpg&quot; /&gt;&lt;/p&gt;

&lt;p&gt;This is also the formula where the discount factor comes from, in cases where we want to see how much money $10.000 in one year would be worth today.&lt;/p&gt;

&lt;p&gt;For interest rates you also need to take into account how many times they are paid per year. 10% annual rate, paid twice a year at 5% each, will give you $1 x (1,05)^2 = $ 1,1025, meaning that the effective interest rate is 10,25%. The power of compounding.&lt;/p&gt;

&lt;p&gt;It starts to get a bit more complicated as we move on to &lt;strong&gt;investment appraisal&lt;/strong&gt;, starting with net present value. Here we use the annuity formula from above. Buying a machine, you look at your cost of funds taking into account:
- interest payable per year for the money required to buy the machine
- the amount of savings you presume to get per year by getting the machine
- the amount of years it will run&lt;/p&gt;

&lt;p&gt;All these savings will then have a set value today. This present value less the cost of the machine is what is called net present value (NPV). In case you get a NPV of 0, the resulting discount rate (1/r = 1 / (1+x/100)^t) is called the internal rate of return (IRR) or yield.&lt;/p&gt;

&lt;p&gt;Another item to use is the payback period, which will simply take the cash flows in each year to see when the machine is paid back. Making it a bit more complicated, you can also discount each cash flow.&lt;/p&gt;

&lt;p&gt;Further issues in NPV are that you need to take into account relevant costs and revenues only. This is best explained through the examples present in the introduction book. In short, think about whether a cash-flow will change if you do what you do. If it does, it's relevant, if it doesn't, it isn't ;)&lt;/p&gt;

&lt;p&gt;Another item is reflected in the fisher equation: (1+ nominal interest rate) = (1+ real interest rate) (1+ expected inflation rate). In reality, it gets more complicated because discounting needs to take into account preference for money now, inflation and a risk premium, which is hard to pinpoint. Another impotant item is that future cash flows might lead to taxes and purchases might be able to be depreciated over time.&lt;/p&gt;

&lt;p&gt;Profitability index is about finding out which project to do. It's calculated by deviding the NPV by the money invested in a year. The higher the PI, the more worthwhile the project to do.&lt;/p&gt;



