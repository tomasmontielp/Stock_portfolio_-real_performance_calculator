# Stock_portfolio_real_performance_calculator
In this notebook, a tool for automatically calculating the real performance of a stock portfolio is developed. Specifically, this tool aims to account for both the capital gain/loss and the dividends the company has paid to the investor.
To do so, the following steps are done:
* **Data preparation:** The csv files from the brokerage account are imported, and the data of each database is prepared for data analysis.
* **Data transformation:** The different databases are used to account for dividend gains and compute the real gain/loss of each stock investment. The results are merged into a final database.
* **Data visualization:** The real performance of stocks is visually compared to the gain/loss indicated by the brokerage account. The importance of accounting for dividends gain is reflected.

All of the steps were done with Python and its libraries.
