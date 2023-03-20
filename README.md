# Cluster_Portfolio_Analysis
***
## This project examines a 35 stock varying weight portfolio loosely based on a colleague's portfolio with similar composition.
***
## Quantitative analytics performed on the portfolio included component correlation and interaction, a benchmark comparison, distribution of returns analysis and sharpe ratio analysis. 
***
## Furthermore, a "deep dive" into the components of the portfolio was undertaken and numerous metrics including valuation & performance were examined.
***
## Primary tools used in the project were:
* OpenBB SDK - quick & easy access to stock data on all components of the portfolio.  Further "deep dive" into certain metrics fo the portfolio was also achieved through application of just a few of the hundreds of available functions.  
    * https://docs.openbb.co/
* Riskfolio-Lib - portfolio optimization library that was used to explore how the components of the portfolio "interacted" via correlation & clustering analysis
    *  https://riskfolio-lib.readthedocs.io/
***
## Summary
* This project was an excellent case used to explore two very powerful analysis tool kits; OpenBB SDK & Riskfolio-Lib
* Through use of the OpenBB SDK stock data of portfolio components was quickly and easily obtained ready for further analysis.
* The use of Riskfolio-lib allow for the examination of correlation and interaction of portfolio components. A minimum spanning tree analysis and asset cluster map gave excellent insight to the interactions of the stocks in the portfolio.
* The OpenBB SDK allowed for the analysis to dive deep into the components of the portfolio and start to examine multiple valuation and performance metrics.
***
## Follow On
* At this point in the project, the analysis could take a number of different directions depending on the end user/client objectives.  Some possible avenues to explore are:
    * Portfolio rebalancing/reduction based on cluster analysis
    * Portfolio optimization around risk parameters (Sharpe optimization, risk parity ...)
    * Predictive analytics utilizing current data frames of performance and valuation data.
    * Portfolio hedging