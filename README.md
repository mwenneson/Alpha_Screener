# Alpha_Screener
Applying CAPM to determine alpha and beta of stock excess returns, taken from Dr. Abdullah Karasan.

Asset Pricing Model¶
Financial investment decision is a function of risk and return, which are positively related to each other. Investor tries to obtain highest possible return while mitigating the risk as much as possible. So, in a nutshell, investor tend to invest in an asset with best risk-return combination. But the question is how can we estimate the best risk-return combination?

This lesson tries to tackle this question using two celebrated models. In this part of the lesson, we will discuss the two prominent models about asset valuation:

Capital Asset Pricing Model (CAPM)

It is an easy task to measure return of an asset, which is nothing but a change in an asset's value based on previous period. How about risk? It is exactly where Markowitz's Portfolio Theorycomes into the picture. Markowitz's article titled "Portfolio Selection" provides a clear definition of what had hitherto been unambiguous.

This trade-off is defined as the selection problem of the portfolio mean and variance of the assets, and given the risk level the theory has suggested that high expected return should be selected. Expected return and risk are given as follows:

Expected Return=𝔼(𝑅𝑖)
 
Risk=𝜎(𝑅𝑖)
 
where  𝑅𝑖  is the return of ith asset and  𝔼  denotes expectation operator, and  𝜎  represents the standard deviation of return. Thus, standard deviation is assumed to be a risk of an asset and this approach paves the way for further analysis.

In order to better understand and handle the risk in finance, we need to differentiate it:

Systematic Risk: It is the that cannot be disappeared by diversification. Therefore it is also referred to as non-diversifiable risk. More specifically, random fluctuations in the value of an asset can be balanced out by holding diverse assets. Some systematic risks are:
Interest rate risk
Inflation risk
Market risk
Unsystematic Risk: It is the risk that can be mitigated through diversification. That is random fluctuations in the value of the asset can be balanced out by holding many different assets. Unsystematic risk arises from Stock-specific issues. Some unsystematic risks can be listed as:
Business risk: Any Internal weakness of a company can jeopardize its profitability
Financial risk: Change in capital structure allocation of a company
Entrance of a new competitor
CAPM examines the systematic risk ( 𝛽 ) and expected return in a competitive market. It is a parametric and univariate approach. The ultimate aim of this method is to price an individual security or a portfolio. Let's now talk about the components and the formula of CAPM:

𝔼(𝑅𝑖)=𝛼𝑖+𝛽𝑖𝔼(𝑅𝑚)
 
where

𝑅𝑖 : Expected excess return of the  𝑖𝑡ℎ  stock
𝛼𝑖 : asset’s return\loss independent of market return (y-intercept)
𝑅𝑚 : Expected excess market return
𝛽𝑖 : Slope coefficient
Here, excess return represents the portion of an individual stock or market return above the risk free rate. Or it can be formulated as:

𝔼(𝑅𝑖)=𝔼(𝑟𝑖)−𝑟𝑓
 
where  𝑟𝑓  is risk free rate and  𝑟𝑖  is the individual stock return. So, excess return checks if an asset yields larger return than a safe asset. If so, it is a motivation to invest, otherwise, investor prefer to invest in a safe asset whose return is low but guaranteed.

The result, denoted as  𝔼(𝑅𝑖) , is also the required return or discount rate used in valuing an asset or a project that we discuss in NPV lesson:

Required Rate of Return = Risk Free Rate of Return + Beta*(Market Return – Risk Free Rate of Return)

Thus, CAPM can be defined as:

𝑟𝑖−𝑟𝑓=𝛼𝑖+𝛽𝑖(𝔼(𝑟𝑚)−𝑟𝑓)+𝜖𝑖
 
where

𝜖𝑖 : Error term
We need to put special emphasize on  𝛽 , which shows the extent to which an investment adds risk to a portfolio. Put differently, it is a measure of systematic risk of a stock in comparison to the market. It is also indicates the correlation between individual stock and market:

If the  𝛽 >1, stock is riskier than the benchmark market
If the  𝛽 =1, stock is as riskier as the benchmark market
If the  𝛽 <1, stock is as less riskier as than the benchmark market
