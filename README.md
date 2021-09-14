# Airplane-Prices

I am not sure if it is because I am Korean, but I love traveling to Korea. Because of this, I wanted to know the best time to buy a ticket to Korea for the cheapest price. I created a webscraping code to get the costs of a 1 week or less round trip to Korea and analyzed the data. The round trip is within 1 week, because I will start working soon and most work vacations are usually around 1-2 weeks. Of course this would not be useful right now, because covid enforces the 2-week quarantine. However, I hope this will be useful in the future.

## What I learned
I learned how to web scrape using Selenium and was able to manipulate the data to a readable format (data frames). I was also able to learn how to create better looking boxplots and include interactions of the categories into the boxplots. At the end, I tried to create a linear regression model using the airline data to predict the costs of tickets, but the model did not accurately predict the cost of the airplane tickets. However, I was able to learn how to create a simple linear regression model using sklearn. 

## Problems
Because the web browser took a minimum amount of 50 seconds to load per page, it almost took 2 hours to gather the data I have now. I also thought I was webscraping the data wrong, because the price data kept changing. But this was because airplane ticket prices change depending on the date you purchase them. Therefore, the first month of data I collected may not be useful, because purchasing a ticket within the first month of purchase will always be much higher than the next few months. 
