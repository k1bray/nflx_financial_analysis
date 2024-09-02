<p align="center"><img src="https://github.com/k1bray/stock-price-analysis/blob/main/Visuals/netflix_white_background.jpg" /></p>

# Introduction
Netflix began as an idea in 1997 by Reed Hastings and Marc Randolph that would give consumers the ability to rent DVDs through the mail via a website instead of having to go to a store.  Their website and business officially launched in 1998 with their subscription service coming soon after in 1999 that offered unlimited DVD rentals without due dates, late fees, or monthly rental limits.  The company was brought public on May 23, 2002, with an initial public offering (IPO) on NASDAQ for the ticker symbol: NFLX.  Innovative features to the user experience over the years, such as a personalized movie recommendation system based on customer’s movie ratings, and successfully transitioning the company’s focus to streaming services has helped to bolster revenue as well as the stock price to its current level.  

### Disclaimer
This report is for informational purposes only and should not be considered financial advice. The information presented is based on publicly available data and does not constitute a recommendation to buy or sell any securities, including NFLX stock. Investing involves inherent risks, and you should always conduct your own research and due diligence before making any investment decisions. Consider consulting with a qualified financial advisor to discuss your specific investment goals and risk tolerance.

# Table of Contents
[Summary of Project Intention](https://github.com/k1bray/stock-price-analysis/blob/main/README.md#summary-of-project-intention)

[Dataset Examination and Profiling](https://github.com/k1bray/stock-price-analysis/blob/main/README.md#dataset-examination-and-profiling)

[Cleaning and Manipulation of Data](https://github.com/k1bray/stock-price-analysis/blob/main/README.md#cleaning-and-manipulation-of-data)

[Analysis and Discussion](https://github.com/k1bray/stock-price-analysis/blob/main/README.md#analysis-and-discussion)

[Conclusion and Possible Further Actions Based on Analysis](https://github.com/k1bray/stock-price-analysis/blob/main/README.md#conclusion-and-possible-further-actions-based-on-analysis)

# Summary of Project Intention

The intended purpose of this project is to take a closer look at the Q1’24 financial statements for NFLX that were released on April 18, 2024.  This was done by calculating various metrics that utilize the available objective data.  An attempt was made to gain insight into the overall financial health of NFLX. 

### Tools Used for Analysis
There were multiple tools used in the process of this analysis.  Microsoft Excel was used to view financial statements from NFLX.  Microsoft Word was used as the main platform for writing and editing the report of the analysis.  Microsoft Excel was used to create the visuals.  GitHub Desktop and GitHub were used as a hosting source for the version control and final rendering of the project report for publication.

# Dataset Examination and Profiling

### Data Availability and License

The publicly available NFLX financial data used for this project can be accessed [here]( https://s22.q4cdn.com/959853165/files/doc_financials/2024/q1/Q1-24-Website-Financials.xlsx).

The tables used during this analysis are of typical accounting format consisting of a balance sheet, income statement, and a statement of cashflow.  Additionally, there is another table that contains figures for streaming revenue and membership information by region.  However, this table was not utilized for the purposes of this analysis.

# Cleaning and Manipulation of Data

Data was parsed out of the aggregate and isolated as necessary for analyzation and creation of visualizations using Microsoft Excel.  Original data was footnoted as being presented in thousands unless otherwise labeled.  When necessary, figures were adjusted for axes and data label formatting as appropriate for rounding and proper decimal placement.

# Analysis and Discussion

## Analysis of NFLX Financials

### Overall Performance
#### Top-line Revenue
 
![Top-Line Revenue](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/01_revenue.png)

Over the past 9 quarters NFLX has seen somewhat of a general upward trend in their quarterly revenue figures.  When compared to the quarterly earnings report for the three months ending on 03/31/2024, the same period from two- and one-year previous has seen top-line revenue increases of 16% and 12.9%, respectively.  However, the year-over-year (YOY) increase between Q1‘22 and Q1‘23 was only 3.6%.

![Quarterly % Change in Revenue](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/02_quarterly_%25_change_in_revenue.png)

The consistency of revenue growth seen in the chart above demonstrates the strength of the NFLX business model, as well as their placement among their competitors with respect to capturing market share.  Although the data being analyzed is from a relatively short timeframe, the current trend appears promising.  The chart above shows the percent change quarter-over-quarter for top-line revenue exhibiting an upward trend over the past 2 years.

#### Net Income & Operating income
 
![Net & Operating Income](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/03_net_%26_operating_income.png)

In the chart above, the difference between the net and operating income represents the non-operating expenses for that quarter.  Where they get wider apart from each other shows areas where NFLX was potentially less efficient at controlling those non-operating expenses.

They are showing an overall positive trend in their operating Income, and in fact saw a 53% year-over-year increase in Q1’24 to $2.63 billion.  This is up from Q1’23 with $1.71 billion.  Overall, it appears that NFLX has been gaining ground on its ability to control operating costs, even if there have been a few unexpected variables along the way.

Q4’22 saw a one-time expense that had a great effect on the net income [Morningstar.com](Netflix’s Q4 Earnings Show a Comeback in Subscriber Growth | Morningstar).  The impact of this one-time event was felt in multiple sections of the financial reports.  The explanation given by NFLX for the event was that it was related to the revaluation of European debt which came about due to the depreciation of the US dollar vs the euro.   

NFLX historical performance has not been without its struggles. They maintained solid growth in subscribers until the early part of 2022 when they experienced their first net subscriber draw-down ([Statista.com](https://www.statista.com/statistics/250934/quarterly-number-of-netflix-streaming-subscribers-worldwide/)). This came off the heels of a viewer surge during the COVID-19 pandemic.  The drawdown (or what could be more accurately described as a stagnation of subscriber growth) will be discussed in more detail in a later section covering subscriber growth rates.  Q4’22 was when they launched their lower-priced ad-supported subscription service, which has since helped to bolster their overall subscriber base as well as revenues ([CNBC.com](https://www.cnbc.com/2024/05/15/netflix-ad-tier-has-40-million-users.html)).  This also trickled down to their net income with a positive effect.

NFLX implemented price increases in certain regions during Q1’22 which led to some minor subscriber churn ([Antenna.com](https://www.antenna.live/post/netflix-q122-retrospective#:~:text=The%20company%20raised%20prices%20on,'21%20and%20Q4'21)).  However, any short-term slowdown in subscriber growth due to the new higher prices has contributed to their current ability to increase profits and revenues as they continue to expand their customer base.

#### Net Profit Margin & Gross Margin

![Net Profit Margin vs Gross Margin](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/04_net_profit_margin_vs_gross_margin.png)

Since Net Profit Margin is a metric that shows what percentage of each revenue dollar is being converted into profit, the chart above shows that NFLX has been a bit of a mixed bag in that ability over the past 9 quarters.  Although the long-term trend may indicate improvement, it shows that NFLX has been rather inconsistent in its efficiency of managing the conversion of revenue to profit with consideration of total costs.  However, the dips in both margins for Q4’22 and Q4’23 can be explained in the context of the reported one-time charges previously mentioned.

Over the past two years NFLX has seen some variability in their gross margins.  However, the prevailing trend is positive with the lowest period (Q4’22) showing 31% of revenue retained as gross profit.  After incurring the costs for content creation, streaming services such as NFLX have the potential to significantly benefit from overall low marginal costs.  This gives them the ability to maintain lower gross margins, relatively speaking, and still remain quite competitive in their market.

The lowest net profit margin was 1% in Q4'22, and the highest was 25% in Q1'24, while the operating margin ranged from 7% in Q4'22 to 28% in Q1'24. In most quarters, the net profit margin is only 1-2 percentage points higher than the operating margin.  This close similarity was the reason for excluding the operating margin from the chart above.

Since the operating margin is very similar to the net profit margin, this suggests that Netflix might have relatively low non-operating expenses (expenses not directly related to core operations). This can be a positive sign for its financial efficiency.

#### Earnings Per Share (EPS)

![EPS Basic](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/05_eps_basic.png)

The EPS for NFLX has fluctuated over the last 9 quarters, with Q4'22 and Q4'23 showing the lowest EPS. While there isn't a clear upward trend in EPS, Q1'24 showed a significant increase compared to the previous quarter.

It's important to consider this EPS variability in the context of the profit margin and revenue growth trends presented earlier in the report. While revenue growth has been positive, with some quarters showing strong gains, the profit margin hasn't necessarily followed the same upward trajectory. This disconnect between revenue growth and profit margin could explain some of the fluctuations in EPS.

These fluctuations can also be influenced by one-time events or factors specific to the streaming industry as well as the potential effects from NFLX engaging in a stock buyback strategy that is discussed later. Further analysis could be beneficial to isolate the specific drivers behind the EPS variations observed in Q4'22, Q4'23, and the positive change in Q1'24, as well as to quantify the effects of the stock buyback strategy as it reduces the number of outstanding shares with which to calculate EPS.

#### Asset Turnover Ratio

![Asset Turnover Ratio](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/06_asset_turnover_ratio.png)

Higher values for the asset turnover ratio indicate improving efficiency in utilizing assets to generate revenue.  The recently increasing values of the Asset Turnover Ratio shows that NFLX may be gaining ground in that ability.  If this trend can be maintained, it could be an indicator that the upward trend in top-line revenue might continue in the future.

However, it's important to note that while a rising asset turnover ratio is generally positive, it's not a guarantee of future revenue growth. Other factors like market conditions, competition, and the company's overall strategy also play a significant role.

#### Efficiency Ratios

![ROA vs ROE](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/07_roa_vs_roe.png)

As can been seen in the chart above, there is some variation in the 2-year values for both return on assets (ROA) and return on equity (ROE).  In both cases there were abnormally higher expenses in the section for “Interest and Other Income (Expense)” on the income statement for Q4’22 and Q4’23 that had a general negative impact on the calculated values.  Since both ROA and ROE use the Net Income value in their calculations, which was greatly impacted by these expenses, these events had a significant effect on the results.  However, with continued top-line revenue growth accompanied by a reduction of expenses, there has been a substantial rebound in net income values, which in turn has bolstered the figures for ROA and ROE.

#### Liquidity and Solvency Analysis

![Current Ratio](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/08_current_ratio.png)

The current ratio is a financial ratio that measures a company's ability to pay its short-term obligations using its current assets.  A “healthy” current ratio value range for most companies is generally accepted to be within 1.5 to 3.  NFLX current ratio over the past 2-years has been below that range with a low of 1.05 and a high of 1.33.  However, these figures need to be viewed in the proper context.  The very nature of the business of NFLX being a growth company in the tech and entertainment sector means that they have the latitude to maintain a lower current ratio when compared to other businesses with different business models and capital structure.  They can do this in part because of the structure of their subscription model revenues which provide consistent cash flow to meet short-term obligations.  As an example, they would potentially have much less variability in their cash flows than a company that operates in manufacturing that must maintain a level of current inventory.  Also, being a company in a growth phase, they invest heavily in creative content, which is a long-term asset, along with investments in growth opportunities in an evolving on-demand digital streaming market.

#### Debt-to-Equity Ratio

![Debt-to-Equity Ratio](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/09_debt_to_equity_ratio.png)

The debt-to-equity ratio is a financial ratio that measures the amount of debt a company uses to finance its assets relative to its equity.  NFLX is showing a declining trend in their debt-to-equity ratio.  What this means is that the company is using less debt in relation to the shareholders’ equity.  This indicates improving financial stability with reduced financial risk.  This increases their flexibility to manage their finances, especially during times of an economic downturn or when facing an unexpected financial challenge.

The continued reduction of debt would allow NFLX to invest in creative content with less dependence to take on additional debt.  This could favorably position NFLX with an edge in relation to their competition.  Additionally, the reduction of their debt load in relation to their equity also provides an enhanced credit rating.  This gives NFLX more flexible and available options for funding future investments for growth if they should decide to utilize debt for that purpose.

Although NFLX has historically not offered a dividend and has instead chosen to focus on reinvestment, the downward continuation of this debt trend could open the door to the possibility of future dividend payments to shareholders.

#### Liabilities

![Current Liabilities](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/10_current_liabilities.png)

While reducing assets as of late, NFLX has also been taking on additional liabilities that can be seen in both their current and total liabilities.  However, they have been reducing long-term debt as can be seen below.

![Long-Term Debt](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/11_long_term_debt.png)

![Total Liabilities vs Total Stockholders Equity](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/12%20_total_liabilities_vs_total_stockholders_equity.png)

As can be seen in the chart above, while Total Liabilities have stayed fairly consistent, Total Stockholders’ Equity has generally been increasing, which could be an indication of retained earnings and reinvestment back into the company.

#### Operating Cash Flows

![Operating Cash Flows](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/13_operating_cash_flows.png)

The positive and growing operating cash flow, as can be seen in the chart above, indicates that the company’s core business operations are generating cash.  This can be seen as a positive sign for the company's overall financial health, as it indicates that their core business operations are generating enough cash to cover their expenses and invest in growth opportunities.

NFLX subscriber base has been increasing since a modest drawdown, or a relative pause in growth, in early 2022.  Combined with strategic price increases, the introduction of their budget-friendly ad-supported subscription tier, as well as their increasing efficiency at using assets to generate revenue, have all helped in boosting their operating cash flows.

#### Investing Cash Flows

![14_investing_cash_flows](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/14_investing_cash_flows.png)

Q4’22 obviously stands out in the chart above.  It is marked by a significant drop in the investing cash flows.  It coincides with a previously discussed reportedly large one-time expense.

Beginning in Q1’23, NFLX has engaged in a stock buyback strategy.  FY2023 saw a total stock buyback amount of over $6B, and Q1’24 added another $2B.  As of the report of Q1’24 earnings, NFLX was holding $8.93B of its own stock.  This is considerably higher than the previous year’s Q1’23 earnings report that showed only $1.23B of stock.  It’s possible that the company’s management truly believes that the traded stock price is undervalued and are also confident that the per share price will be higher in the future.  In the short term, it will decrease their investing cash flow and has the potential to impact future growth by limiting their ability to invest in growth opportunities.  Also, by reducing the number of outstanding shares, the strategy can enhance the perceived financial health of the company through a positive effect on EPS values.  This could lead investors to push the traded price higher with stock purchases and offer further benefit to current shareholders through position appreciation and higher returns.

#### Financing Cash Flows

![15_financing_cash_flows](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/15_financing_cash_flows.png)

The Financing Cash Flows for NFLX has been almost solidly negative for the past nine quarters.  A driving factor for this has been their commitment to paying down long-term debt as previously discussed and can also be seen in the positive trend for the ratio of debt-to-equity.  Also, as previously discussed, NFLX has been engaging in a campaign to reacquire a percentage of outstanding shares that can be seen on both the balance sheet and the statement of cash flows.

#### Industry Comparison

| COMPANY                         | SUBSCRIBERS (MILLIONS) | MARKET SHARE |
| :--------------------------- | ---------------------------------: | -------------------: |
| Total Subscribers (Est) | 1800.0                                           | 100%                      |
| NFLX                                     | 269.9                                             | 15.0%                     |
| AMZN Prime Video         | 180.0                                             | 10.0%                     |
| Disney+                               | 153.6                                             | 8.5%                        |
| HBO MAX                           | 99.6                                                | 5.5%                        |
| Paramount+                      | 71.0                                                | 3.9%                       |
| HULU                                   | 50.2                                                 | 2.8%                       |
| Apple TV                             | 44.1                                                 | 2.5%                       |
| Peacock                              | 34.0                                                | 1.9%                       |
| ESPN+                                 | 24.8                                                 | 1.4%                      |
| YouTube TV                       | 8.0                                                    | 0.4%                      | 

With 269.6 million worldwide subscribers, NFLX currently controls the #1 slot in their market with 15% of the roughly 1.8 billion current global streaming subscribers.

#### Subscriber Growth

![16_nflx_monthly_subcriptions](https://github.com/k1bray/nflx_financial_analysis/blob/main/Visuals/16_nflx_monthly_subcriptions.png)

The chart above shows the number of monthly NFLX subscribers by quarter going back to 2013.  Historically until Q1 ’22, NFLX had always seen a positive quarterly expansion of their subscriber base with a quarter-over-quarter average subscription growth rate of 4.4%.  Since 2013, NFLX has had only 2 quarters of negative growth in Q1 ’22 (-0.1%) and Q2 ’22 (-0.4%).  These two quarters have been highlighted on the chart with a box.  Just before the beginning of the Covid-19 pandemic in Q4 ’19, NFLX had 167.09 million subscribers.  The mandated lockdowns caused a surge in subscribers which had ballooned to 221.84 million by Q4 ’21.  Since that time NFLX has gained an additional 47.76 million subscribers which represents an 18% increase during that time.


# Conclusion and Possible Further Actions Based on Analysis

Based on the analysis of key financial metrics, including subscriber growth, top-line revenue, and cash flow, Netflix has demonstrated an overall positive performance.  However, it is crucial to acknowledge that these quantitative findings alone do not provide a complete picture of the company's prospects.  Several qualitative factors, such as the complexities of the streaming marketplace, intense competition, and economic uncertainties, must be carefully considered.

It's important to once again emphasize that past performance is not indicative of future results.  Netflix's historical growth trajectory may not be sustainable without continued innovation and adaptation.  To gain a deeper understanding of the company's potential, further analysis of qualitative factors such as NFLX available content library, international expansion, and competitive positioning is recommended.

The NFLX subscription business model is one that is well poised to generate consistent revenue.  By continuing to focus on improving the quality of their content library as well as the customer experience, NFLX has the potential to maintain their position of market share among their streaming and entertainment competitors.  However, the streaming and entertainment sector is still very much evolving, and it will be important for NFLX to evolve with it to stay relevant in the space, especially as other streaming services are being created and optimized by competitors.

A general recommendation would be warranted for additional in-depth analysis of such areas as content library valuation that includes both original and licensed content, content viewing performance that identifies trends in viewer preferences, direct competitor comparison to NFLX of both quantitative and qualitative metrics, the potential impact that emerging technologies, such as AI, could have on NFLX as the industry evolves going forward, and additional analysis that considers growth potential by region or country.

