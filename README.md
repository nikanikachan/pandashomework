# A Whale Off the Port(folio)
### Unit 4 pandas homework

## Performance Analysis

![Returns](https://i.ibb.co/XkGZHzB/Returns.png)

![Cumulative Returns](https://i.ibb.co/72GXKf7/Cumulative-returns.png)


Based on the plotted daily returns, it is not immediately obvious if any of the portfolios outperformed the S&P 500. However, if we look at the cumulative returns plot, It clearly shows that all portfolios outperformed the S&P 500.

## Risk Analysis

![Box plot](https://i.ibb.co/Wcrxb1v/Boxplot.png)

Tiger Global Management has the largest spread and the S&P 500 has the smallest spread. This seems to indicate that all of the managed portfolios are riskier than the benchmark.

| Portfolio | Annualized Standard Deviation |
| ------ | ----------- |
| BERKSHIRE HATHAWAY INC   | 0.203682 |
| TIGER GLOBAL MANAGEMENT LLC   | 0.171830 |
| Algo 2   | 0.134401 |
| S&P 500   |  0.129133 |
| Algo 1   |  0.126801 |
| SOROS FUND MANAGEMENT LLC   |  0.124487 |
| PAULSON & CO.INC   |  0.110754 |



Berkshire Hathaway, Tiger Global Mgt and Algo 2 portfolios have higher standard deviation than the S&P500.These portfolios are riskier than the benchmark.

## Rolling Statistics

#### Rolling standard deviation

Based on the line graph, the direction of each of the portfolios' returns seems to be in line with the S&P 500.

#### Correlation

The returns of Paulson & Co. Inc most closely mimics the S&P 500. This portfolio has the highest correlation with the S&P 500.

#### Beta

I looked at the beta of Soros Fund Mgt and it shows a low positive beta coefficient of 0.0005. The 60 day rolling Beta shows varying sensitivity to the S&P 500. 


## Sharpe Ratios

Per unit of risk, the data shows that the algo strategies outperform the benchmark. The Algo 1 portfolio has the highest Sharpe Ratio of 1.36, this algo portfolio outperformed both the whale portfolios and the S&P 500. The Algo 2 portfolio outperformed the S&P 500 and all the whale portfolios except for Berkshire Hathaway.

## Custom Portfolio

For the custom portfolio, I chose 3 tech stocks: Amazon, Facebook and Google. I compared a portfolio with each of these stocks equally weighted to the S&P 500, whale portfolios, and algo portfolio returns. Below is a summary of the results

- My custom portfolio is riskier compared to all other portfolios, it has higher standard deviation than the rest of the portfolios.

- My custom portfolio has the second highest sharpe ratio. The Algo 1 strategy has more return per unit of risk compared to my portfolio.

- My custom portfolio is negatively correlated with the S&P 500 but positively correlated with the whale and algo portfolios.

- For Beta, I used the TX 60 index as benchmark. My custom portfolio has a positive Beta which indicates that it generally moved in the same direction as the benchmark.