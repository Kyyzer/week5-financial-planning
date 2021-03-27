# Financial Planning
---
## Part 1
The first section will allow users to visualise their savings composition by investment in different shares and cryptocurrencies. Followed by an assessment of whether they have enough savings for an emergency fund.

1. Cryptocurrency (BTC, ETH) prices are fetched by use of API
2. Share (AGG, SPY) prices are sourced from the Alpaca trading API
3. Crypto and share holdings are consolidated in a savings dataframe 
4. These holdings are compared against an ideal emergency fund

---
## Part 2
The second section features a retirement planning tool that will utilise historical closing prices to run a Monte Carlo simulation and calculate the projected performance for 30 years. Along with this data users can calculate the expected portfolio returns for a particular investment amount.

1. Fetch 5 years of historical data for AGG and SPY from the Alpaca trading API
**note: free version of API only allows 1000 entries, thus unable to retrieve the required 1260**  

2. Configure Monte Carlo simluation to forecast 30 years of portfolio returns  

3. Calculate expected portfolio return at 95% lower and upper confidence intervals based on $20,000 investment

### Optional
1. Calculate expected portfolio return at 95% lower and upper confidence intervals based on \$20,000 investment and only 5 years
2. Calculate expected portfolio return at 95% lower and upper confidence intervals based on \$20,000 investment and only 10 years