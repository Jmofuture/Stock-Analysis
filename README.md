# Stock Analysis
### Real-time Stock Market Dashboard using Power BI

### Visualize historical performance of stocks using area graphs and bar charts in Power BI

## Dahsbord

![image](https://user-images.githubusercontent.com/78714438/168650248-f6288924-ea0b-4508-b20f-dc070af98d4f.png)

[Link to the Coursera project](https://www.coursera.org/projects/build-a-real-time-stock-market-dashboard-using-power-bi)

- Project Overview- Get your Finance API keys.
- Importing financial data using API.
- Creating dashboard- Summary page.
- Creating dashboard- Historical Perormance page.
- Dashboard Automation- Visualizing other stocks.
- The data is composed of historical data for the last 5 years.

[API](https://site.financialmodelingprep.com/developer/docs)

We must register to access the API

![image](https://user-images.githubusercontent.com/78714438/168646585-0bc81338-d91e-4326-a1c8-0c3b82989ac1.png)

When we register, the free option is activated, which allows us to make 250 API requests per day.

![image](https://user-images.githubusercontent.com/78714438/168646687-49d1d66f-9e0f-4b09-974f-d40846846e3d.png)

Once registered we go back to the documentation and we will be given the access Key.

![image](https://user-images.githubusercontent.com/78714438/168646769-3bd88471-02c3-40f3-af12-3bb4713711fc.png)

We will use Company Quote from AZMN(Amazon) 

We just need to change the APPL URL to AZMN.

![image](https://user-images.githubusercontent.com/78714438/168646906-be80a0c1-9bb0-4265-a86f-84f6ecc18a4e.png)

That will not give access to a Json file.

![image](https://user-images.githubusercontent.com/78714438/168647036-aa1449c5-59bc-42a0-a6b3-e0dac109230d.png)

We would copy the URL.

![image](https://user-images.githubusercontent.com/78714438/168647371-d81f3851-c6fc-43bf-bed6-c0aec7b631c5.png)

## Power BI

In the Power BI Get Data menu, look for the Web option.

![image](https://user-images.githubusercontent.com/78714438/168647449-269a6738-57fa-48fa-a511-b80edb4f4d98.png)


In the menu we copy the URL, we can change the Ticker for the financial instrument we want, in this case we will use AMZN (Amazon), but it can be any, where it says YOUR APY we must delete that and place the Key that was assigned to us.

![image](https://user-images.githubusercontent.com/78714438/168647541-61fd11c2-9166-413e-8dcd-1092df2b1bc5.png)

In the next screen click on Connect and the Power Query window will open with the loaded data, click on Close and Apply to load the data.

![image](https://user-images.githubusercontent.com/78714438/168647598-b689d8eb-7541-4c39-834f-19b1aefc1882.png)

When loading we check in Data if loading was successful.

![image](https://user-images.githubusercontent.com/78714438/168647738-43d9a9b0-8baf-4e49-b0e6-9fe85292d1ca.png)

We will then use the historical data to obtain all the price variations suffered by the Stock.

![image](https://user-images.githubusercontent.com/78714438/168647833-28592f96-808c-4e13-acd6-145d80fd685d.png)

We will use the daily price history, but we can choose minutes and hours, we copy the URL as we did before.

![image](https://user-images.githubusercontent.com/78714438/168647918-5df1364c-90e0-4ddf-bcdf-dda0fa929bfd.png)

We repeat the previous steps to obtain the data from WEB We change to the Ticker we are using and enter the KEY, we will obtain the data we requested and Power Query will open. 

![image](https://user-images.githubusercontent.com/78714438/168648025-8148391b-b1d1-403d-9bfe-beccf2ca8538.png)


![image](https://user-images.githubusercontent.com/78714438/168648076-ff34afa1-b685-43d2-b18e-748cdb03883e.png)

We verify that the relationship between the two tables has been created, since the same Ticker (AMZN) or the one you have decided to use should have been generated automatically. 

![image](https://user-images.githubusercontent.com/78714438/168648167-bf8c3e7c-c3a2-4d2e-9c33-98725491e39e.png)

## We begin with Dashborad

- We add a card with the Ticker of the stock.
- We add a card with the opening price.
- We add a card with the highest price.
- We add a card with the lowest price.
- We add a card with the closing price.


![image](https://user-images.githubusercontent.com/78714438/168648552-026b1e59-9e45-4cf8-b837-bde35280954b.png)


Added two filters, by year and month.

![image](https://user-images.githubusercontent.com/78714438/168648742-c30449af-f35e-45c8-8e57-bcde73167503.png)


Scatter chart to determine whether or not share price movements are positively correlated.

![image](https://user-images.githubusercontent.com/78714438/168649062-e948b0e2-9d29-44fe-aafc-f86fcc8afe80.png)

Line graph with historical transaction volume.

![image](https://user-images.githubusercontent.com/78714438/168649267-d35d0b97-bfd9-4573-b0c3-d81812c0f1f6.png)

Candlestick chart depicting daily stock price movements.

![image](https://user-images.githubusercontent.com/78714438/168649491-b6097a20-b619-4d7f-9892-f3f1abd8336c.png)











