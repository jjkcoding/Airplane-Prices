# Airplane-Prices

I am not sure if it is because I am Korean, but I love traveling to Korea. Because of this, I wanted to know the best time to buy a ticket to Korea for the cheapest price. I created a webscraping code to get the costs of a 1 week or less round trip to Korea and analyzed the data. The round trip is within 1 week, because I will start working soon and most work vacations are usually around 1-2 weeks. Of course this would not be useful right now, because covid enforces the 2-week quarantine. However, I hope this will be useful in the future.

## Key Findings
Based on the analysis, I found that the price is much higher if the length of the round trip is 1 day and the trip departs on the month of June or December. The 1 day length round trip is even more expensive if the departure date is within 1 month of purchasing the ticket. The cheapest prices are also found if the round trip is only 4 days. Therefore, the recommended time to get a ticket based on the analysis is any month other than the first month of purchasing the ticket, December, or June and the trip should be a round trip of 4 days. A more indepth analysis can be found in the google colab.

The plot below show these results. The plot does not show two months of data, because the webscraping website only gives 330 future days of data from the day collecting the data.
![ex plot](https://user-images.githubusercontent.com/43764400/133178026-10625792-a907-428f-9c77-e644a4042b0b.png)

## What I learned
I learned how to web scrape using Selenium and was able to manipulate the data to a readable format (data frames). I was also able to learn how to create better looking boxplots and include interactions of the categories into the boxplots. There is still much to learn on graphing in Python and looking forward to the future in learning how to plot these type of datasets.

## Problems
Because the web browser took a minimum amount of 50 seconds to load per page, it almost took 2 hours to gather the data I have now. I also thought I was webscraping the data wrong, because the price data kept changing. But this was because airplane ticket prices change depending on the date you purchase them. Therefore, the first month of data I collected may not be useful, because purchasing a ticket within the first month of purchase will always be much higher than the next few months. Kayak would also only give me 330 days into the future of the airplane ticket prices, so I could not get yearly data.
