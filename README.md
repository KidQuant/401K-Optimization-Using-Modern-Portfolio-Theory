# 401K Optimization Using Modern Portfolio Theory

This project involves a combination of Data Science and Finance theory to construct the optimal 401(k) investment portfolio for possible retirement.

![](https://kidquant.com/post/images/efficient_frontier.jpg)

## Goal

Our goals involved the following:

- **Part 1**: Analyze the historical price trends of 5 different mutual funds involving factors regarding average annualized returns and volatility
- **Part 2**: Engineer scenarios that allow us to create the most optimal portfolio allocation, given the risk and return of our 5 mutual funds
- **Part 3**: Use the optimal portfolio allocation to create what is known as the "Efficient Frontier" using what we know about Modern Portfolio Theory

This analysis will allow us to efficiently allocate a hypotheical investment budget any preferred asset class, not just mutual funds.

## Data

I used data from the Yahoo Finance API, which provides daily, weekly, monthly, and annual historical and real-time information on a wide range of assets, including stocks, options, commodities and exchange-traded funds. We only used two years worth of asset pricing data.

### Enviroment and Tools

1. Jupyter NoteBook
2. Numpy
3. Pandas
4. Matplotlib
5. Scipy
6. Seaborn
7. datetime
8. yFinance (formally known as `fix_yahoo_finance`
