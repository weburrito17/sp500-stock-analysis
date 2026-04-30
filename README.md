# S&P 500 Stock Analysis: What 1.8 Million Trading Days Reveal About America's Top Companies

**Dataset:** S&P 500 Stocks Historical Data from Kaggle  
**Tool:** Malloy + DuckDB  
**Rows:** 1.8 million daily trading records across 500 companies

---

## The Question That Started It All

I always knew the S&P 500 represented the top 500 publicly traded companies 
in America, but I wanted to see the individual effect that each company had 
on the overall market. When one company gains, another loses — and I wanted 
to see that story in the actual data.

"Which companies truly dominated the S&P 500 — and does the most traded 
stock always have the highest price?"

What I found completely changed how I think about the stock market.

---

## What I Found

### 1. The Most Expensive Stocks Are Not The Most Famous
The top 10 highest average closing prices were led by MTD (Mettler-Toledo) 
at $645, followed by EQIX at $426 and TDG at $394. These are not household 
names — most people have never heard of them. Yet they quietly sit at the 
top of the S&P 500 by price. The stocks that dominate financial news are 
not always the most expensive ones.

![Top 10 Highest Average Stock Prices](screenshots/Highest_Prices.png)

### 2. The Cheapest Stocks Are Not The Weakest
The lowest average closing prices included NVDA (Nvidia) at just $13.81, 
RF at $13.42, and HPE at $14.47. Seeing Nvidia on this list was shocking 
— today Nvidia is one of the most valuable companies in the world. Its 
historically low average price tells the story of a company that grew 
explosively before most people noticed.

![Lowest Average Stock Prices](lowest_prices.png)

### 3. The Biggest Price Swings Belong To The Same Names
MTD had the largest price range of any stock at $1,608 from its lowest 
to highest point ever. TDG followed at $1,395 and NFLX at $929. These 
stocks made investors either very rich or very poor depending entirely 
on when they bought in. High price does not mean stable price.

![Biggest Price Swings]((screenshots/top10_prices.png)

### 4. NVDA — The Most Surprising Finding In The Entire Dataset
The single most interesting discovery was Nvidia. It had one of the 
lowest average stock prices historically at $13.81, yet it was by far 
the most traded stock in the entire S&P 500 with an average of 497 
million shares traded per day — more than 5 times the second place 
stock TSLA at 96 million. On top of that Nvidia appeared on the most 
stable stocks list with a daily volatility of just $0.525.

This tells a remarkable story — investors were buying Nvidia in massive 
volumes long before its price reflected how valuable it would become. 
The market knew something the price tag did not.

![Most Traded Stocks](most_traded.png)

### 5. The Most Volatile Stocks Move Nearly $15 Per Day
MTD topped the daily volatility list at $14.81 average daily price 
swing, followed by EQIX at $9.55 and TDG at $8.83. These stocks are 
not for nervous investors — their price can move more in a single day 
than some stocks move in a month.

![Most Volatile Stocks](most_volatile.png)

### 6. The Most Stable Stocks Are The Ones Nobody Talks About
The most stable stocks with the lowest daily volatility were RF at 
$0.358, T (AT&T) at $0.359, and HPE at $0.367. These stocks barely 
moved day to day. Interestingly NVDA also appeared on this list — 
proving that high volume does not always mean high volatility.

![Most Stable Stocks](most_stable.png)

### 7. The Stocks With The Most Growth
The biggest overall growth from lowest to highest price was led by 
MTD at $1,608, TDG at $1,395, and NFLX at $929. These are the stocks 
that rewarded long term investors the most — but also carried the most 
risk along the way.

![Biggest Growth Stocks](growth.png)

---

Dataset source: [https://www.kaggle.com/datasets/your-dataset-link](https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks)

---

## How To Run This Yourself

1. Download the S&P 500 dataset from Kaggle
2. Install the Malloy VS Code Extension
3. Clone this repo
4. Place `sp500_stocks.csv` in the same folder as `analysis.malloy`
5. Open `analysis.malloy` in VS Code
6. Click **Run** above any query

---

## Who Would Care About This?

Individual investors, financial analysts, and portfolio managers would find 
these findings directly useful. The data shows that the most expensive stocks 
are not always the most traded, and the cheapest stocks are not always the 
weakest investments. These findings challenge some of the most common 
assumptions people make when looking at the stock market.

For everyday investors, the biggest takeaway is that price alone means nothing. 
MTD sits at the top of the price list at $645 average but most people have 
never heard of it. Meanwhile Nvidia was sitting at $13 for years while 
investors were quietly buying it in record volumes — 497 million shares per 
day on average. If you had looked at price alone you would have ignored Nvidia 
completely. If you had looked at trading volume you might have noticed something 
was happening before the rest of the world caught on.

For financial analysts and portfolio managers this data raises an important 
question about volatility versus stability. The most volatile stocks like MTD 
and EQIX swung nearly $15 per day on average — meaning huge potential gains 
but also huge potential losses depending on timing. The most stable stocks 
like RF and AT&T barely moved at all. A smart portfolio strategy might 
involve balancing both — stable low volatility stocks as a foundation with 
high volume high growth stocks like Nvidia mixed in for upside.

For stock market researchers and data scientists this analysis shows how 
powerful even basic Malloy queries can be when applied to a dataset of 
1.8 million rows. Patterns that would take hours to find manually in Excel 
appeared instantly — like the fact that the most traded stock was also one 
of the cheapest and most stable, which is a completely counterintuitive finding.

Finally for students studying business or finance this project is a reminder 
that the stocks that dominate the news are not always the ones dominating 
the market. The S&P 500 is full of quiet winners that never make headlines. 
Understanding how to read volume, volatility, and price range together tells 
a much richer story than just looking at which stocks are trending on social 
media. The next Nvidia is probably already in this dataset — trading at a 
low price, moving stable, but with millions of shares changing hands every 
single day.

---
*Analysis by Nicholas Granda | Built with Malloy | Data from Kaggle*
