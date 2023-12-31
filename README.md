# weekly-trading-homework

Tools and utilities to help get starting performing weekly trading homework. 

**USE AT YOUR OWN RISK**: [These materials are released under MIT license unless otherwise noted.](LICENSE) None of these tools will help you get rich quick. They provide an overview in the general market action that you can take 20 minutes a week to look at to provide yourself with a reference to what is is going on in the market.

## Background

I think financial / trading newsletters are more often than not a waste of time and money. I don't think anyone should pay for newsletter or put much importance on what they say. Newsletters at best deliver some small nugget of useful information and at worst put the reader in the mindset of a spectator (which is usually the case). 

Think about it. 

Are you a better fighter because you've watched UFC? Know a lot about driving cars because you've seen a F1 races? A better gymnast because you watched the Olympics?

You might pick up some small technique or thing to try while watching - but only if you are actively engaged in these activities.

Ya gotta do the work yourself as it's really the only way to synthesize the data into your brain - otherwise, **you're just a spectator**. 

I've decided to dump all the tools I've been using to generate weekly updates in hopes that folks might find them useful in doing their own homework. I hope you modify these materials for yourself. They are purposefully designed to be not predictive - this is your brain's job. The tools help one think about the overall context of the market and what is happening in it without noise from the news or social media.

## Contributions

If you have other resources you look at each week, I would love to add them to the list. I want to ensure that anything added to the list is free / low cost and is not predictive or prescriptive in nature. Feel free to make a Pull Request or create an Issue with the resource. 

## Tools

* [Excel](https://www.office.com/)
* [thinkorswim](https://www.schwab.com/trading/thinkorswim)
* [Python](https://www.python.org/)


You can load any of the thinkorswim resources with the `Open Shared item...` menu option under `Setup` in the upper right.

![Load Shared Item](thinkorswim_load_shared_item.png)

## Contents

| Resource | Description |
| --- | ---------------------- |
| [thinkorswim Swing Chart (IWM)](http://tos.mx/HdaqUxy) | Get a reference to the levels and recent price action of IWM. |
| [thinkorswim Volatility Chart (RVX)](http://tos.mx/91xLD9x) | Check where volatility has been clustering / moving lately and in the recent past. |
| [thinkorswim Breadth Chart](http://tos.mx/yzH2mzL) | Look at the general disposition of the market |
| Volatility Cones | Get a reference to the current state of IV compared to HV along different timeframes. Not included as current code is using the thinkorswim developer API which you can no longer get an API key. The API will be disabled soon and I will have to figure out a new way to get this data... or if it is even worth the time. I will add this in the the repository if I update the code in a way that others can use. | 
| [sectors Excel Sheet](sectors.xlsx) | Displays different sectors and relative performance. Can easily be changed to use any symbol that Excel supports by changing the instruments on the top of the data tab (B1, I1 and so on). I usually make them stock data types using the data ribbon. Requires subscription to Office 365.<br/><br/> ![Excel Ticker Change Example](excel_ticker_change_example.png)|
| [global_equities Excel Sheet](global_equities.xlsx) | Copy and paste of sectors Excel sheet with different tickers that I like to compare |
| [thinkorswim Weeklies with Earnings Scan](http://tos.mx/hhCQlH0) | Scan for instruments that <br/>- have earnings coming up <br/>- have weekly options <br/>- liquid |
| [thinkorswim Days to Earnings Report (er_days)](http://tos.mx/wTGX9rH) | Used with the Weeklies with Earnings Scan to sort the list in the watchlist. Import the script and use the customize wheel on the top right od the watchlist widget. <br/><br/> ![Earnings Watchlist](earings_watchlist.png) |
| [CME FedWatch Tool](https://www.cmegroup.com/markets/interest-rates/cme-fedwatch-tool.html) | Gives current market generated probabilities for Interest Rates |


