# Korea Flight Prices: Project Overview
* Web scraped airplane ticket prices using Selenium and "kayak.com"
* Cleaned and split the data into sections for data visualization
* Formed multiple box plots to discover the best time to buy airplane tickets
* **Main Packages:** pandas, numpy, selenium, matplotlib, seaborn

## Purpose
I am not sure if it is because I am Korean, but I love traveling to Korea. Because of this, I wanted to know the best time to buy a ticket to Korea for the cheapest price. I created a webscraping code to get the costs of a 1 week or less round trip to Korea and analyzed the data. The round trip is within 1 week, because I will start working soon and most work vacations are usually around 1-2 weeks. Of course this would not be useful right now, because covid enforces the 2-week quarantine. However, I hope this will be useful in the future.

## Key Findings
#### Note: These key findings are only referenced to round trip airplane ticket prices from LAX to SEL recorded in August 2021
* One day round trips are more expensive than longer day roundtrips
* June and December are much more expensive months
* Cheapest prices are found in 4 day round trips


## Plots of Key Findings:
#### Note:
* Only 330 days of data can be collected, so July and August are missing
* If you are in github dark theme mode, you will not be able to see the black labels of the plot

![ex plot](https://github.com/jjkcoding/Airplane-Prices/blob/main/images/airplane_prices_day_diff.png)
![ex plot](https://github.com/jjkcoding/Airplane-Prices/blob/main/images/airplane_prices_month.png)

## What I learned
I learned how to web scrape using Selenium and was able to manipulate the data to a readable format (data frames). I was also able to learn how to create better looking boxplots and include interactions of the categories into the boxplots. There is still much to learn on graphing in Python and looking forward to the future in learning how to plot these type of datasets.

## Problems
Because the web browser took a minimum amount of 50 seconds to load per page, it almost took 2 hours to gather the data I have now. I also thought I was webscraping the data wrong, because the price data kept changing. But this was because airplane ticket prices change depending on the date you purchase them. Therefore, the first month of data I collected may not be useful, because purchasing a ticket within the first month of purchase will always be much higher than the next few months. Kayak would also only give me 330 days into the future of the airplane ticket prices, so I could not get yearly data.
