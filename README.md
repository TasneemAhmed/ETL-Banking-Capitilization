# ETL-Banking-Capitilization
1. Extract Banking Market Capitilization (the value of a bank that is traded on the stock market, calculated by multiplying the total number of shares by the present  share price.)
   
   Download data in json format and convert it to Pandas Dataframe
   ![extract2](https://user-images.githubusercontent.com/49993791/185780251-2283b111-b3c7-4d26-9aae-449e1577e674.PNG)

2. Transform Data: Convert Market Cap (US$ Billion) column from USD to GBP(exchange rate for British pounds)
![transform2](https://user-images.githubusercontent.com/49993791/185780341-b3ee7454-66d0-4d9b-8912-09c473c85cdb.PNG)

3. Load transformed dataframe into CSV file
4. Log Data means know time of starting & ending of Extract phase...etc
