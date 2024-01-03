# Real Estate Stock Analysis 

This project includes exploratory analysis of several global real estate ETFs. ETFs are "exchange traded funds" and are comprised of a weighted basket of individual stocks, in this case many Real Estate Investment Trusts (REITs) and real estate development companies. 

The project looks at ETFs from UK, USA, China, Japan, Australia, and Europe and can be used to gain a top level understanding of how the general real estate market is performing in these regions. 

The notebook containing the code is named "Real Estate Stock Analysis" imports data from https://uk.finance.yahoo.com/ through the yfinance python package and analyses price and volume trends across the various regions and visualises a several moving averages. 

A summary of the ETFs are shown below: 

| Country/Region    | Ticker (LSE) | Index Name                            | Currency|  Description                          |
| ----------        | ------------ |---------------------------------------|---------|----------------------------- |
| USA               | VNQ          | Vanguard Real Estate Index Fund       | USD | A fund that invests in various US RE REITS across multiple asset classes, the top 3 asset classes being telecoms towers (13.7%) retail, (12.6%) and industrial (12.2%)|
| UK                | IKUP.L       | iShares UK Property UCITS ETF         | GBP | A fund managed by blackrock which is composed of UK REITs, the major holdings are SEGRO (19.18%), Land Securities Group (9.2%) and British Land REIT (6.54%) |                                                                     
| China             | CHIR         | Global x MSCI China Real Estate ETF   | USD | An index consisting of various chinese real estate companies.                                                                         |
| Japan             | 1633.T       | Next Funds TOPIX-17 Real Estate ETF   | JPY | Japanese Real Estate ETF                                                                        |
| Australia             | VAP.AX       | Vanguard Australian Property Securities Index ETF  | AUD |      Australian Real estate fund consisting funds investing in Residential, office, retail and Industrial assets                                                                       | 
| Europe            | IPRP.L       | iShares European Property Yield UCITS | GBP | Index consisting of listed European REITS in developed European countries excluding the UK                                                                    |     

