# ETL-Banking-Capitilization
1. Extract Banking Market Capitilization (the value of a bank that is traded on the stock market, calculated by multiplying the total number of shares by the present  share price.)
   
   Download data in json format and convert it to Pandas Dataframe
   ![extract](https://user-images.githubusercontent.com/49993791/185780582-80b7e1ff-a89f-48f8-8db2-4e1afc2f3d7e.PNG)

2. Transform Data: Convert Market Cap (US$ Billion) column from USD to GBP(exchange rate for British pounds)
![transform](https://user-images.githubusercontent.com/49993791/185780588-6d3250d9-a3b3-4298-8db8-587e4a9d9267.PNG)

3. Load transformed dataframe into CSV file
4. Log Data means know time of starting & ending of Extract phase...etc
