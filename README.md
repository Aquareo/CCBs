# CCBs
Some research on the factors of CCBs and A trading strategy 

This project presents a research study focused on the selection strategy of Chinese Convertible
Bonds (CCBs). We propose an enhanced rotational multi-factor quantitative model for CCB selection based
on machine learning techniques. Our objective is to design and select factors that accurately reflect market
information and construct a multi-factor CCB selection model capable of achieving stable excess returns.
To address the first goal, we conduct a single-factor Information Coefficient (IC) analysis using daily frequency data. We discuss the inherent relationship between IC analysis and regression analysis, highlighting
the limitations of the IC method in determining factor monotonicity. To overcome this limitation, we introduce a stratified backtesting approach. Stocks are divided into multiple tiers based on factor values, allowing
for comprehensive backtesting and performance evaluation of each tier. This approach enables a thorough
assessment of factor effectiveness and monotonicity.
Regarding the second goal, we construct a rotating multi-factor stock selection framework based on various
machine learning models, including SVM, MLP, and XGBoost. We compare this framework with traditional
multivariate linear regression models and the Double Low rotation strategy. Backtesting results are evaluated based on returns, Sharpe ratio, maximum drawdown, and VAR across multiple dimensions. Results
indicate that having more factors does not necessarily lead to better performance. Factors such as conversion
return, bond return, YTM, inventory, and Double Low exhibit higher effectiveness. In terms of machine
learning algorithm selection, SVM demonstrates the highest and most stable average returns among various
factor selections, while algorithms like XGBoost and MLP exhibit greater volatility due to changes in factor
selection.
To further validate the effectiveness of our approach, we implement a multi-factor stock selection strategy
based on SVM using the aforementioned conclusions. Through live trading simulations spanning 118 trading
days (from February to July 2023), we achieve a return rate of 7.94%.
