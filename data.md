# Data Challenge

## Exercise 1

Señor Bayes is on our top 10 delivery man in Mexico City. Since he always want to grant a ★★★★★ rating and know the best roads through the city he normally makes a delivery at a 40 km/h speed to make sure he won’t break any beer bottle in the way to the client but speed up close to the city speed limit of 70 km/h with the same path to go back to get more deliveries as soon as possible. Eli, our operational manager want to make some metrics on delivery man availability and need to calculate the average speed for the whole delivery process of the stores. What, is the average speed performed by Señor Bayes on the delivery described above?

## Exercise 2

Bob is the beer bottling line manager and was late to stop the machine when it alarmed about defected bottles in one six-pack. Five packs passed and shuffle themselves at the packaging station. It is known that sometimes a six-pack is packed with fragile bottles produced by other brewries. The fragile bottles weight 90 grams each and the regular bottles weight 100 grams. Consider that all the bottles at a six-pack have always the same weight. How Bob can figure out which of the 5 six-packs contain the defected bottles using the precision scale only once.

## Exercise 3

AB InBev is a company that brew and distribute the best beers all over the world. It has a very strong presence in the United States, Canada, Western Europe and Brazil. These are referred to as developed markets. AB InBev also has a small presence in other countries, which are called the emerging markets. The head of AB InBev has asked a ZX-Ventures team to investigate opportunities for the company to increase its sales in emerging markets in an effort to depend less on the United States  and Europe market for its sales. The following table shows historic, current, and projected data on sales of beer in different parts of the world.

| Size of Beer Markets    | Market size 4 years ago | Market size today | Market size in 10 years |
|-------------------------|-------------------------|-------------------|-------------------------|
| North America           | 96                      | 156               | 393                     |
| Other developed markets | 138                     | 142               | 190                     |
| Emerging markets        | 52                      | 61                | 134                     |

The head of AB InBev has asked the ZX-Ventures team to decide on ten specific countries to investigate more thoroughly. Based on this investigation, he directed the team to identify up to five countries where they predict additional investment in AB InBev operations will show the greatest return over the next 10 years.

Based on the opinion of the head of AB InBev, which of the following statements is a valid conclusion?

- The head of AB InBev believes that the main growth in the world’s beer sales over the next 10 years will be derived from emerging markets;

- The head of AB InBev believes that the major growth in emerging markets’ beer sales will be greatly affected by the growth in the US market;

- The head of AB InBev wants to invest more money in the company’s emerging markets branches relative to the US branch;

- The head of AB InBev wants the company’s future sales growth in emerging markets to increase relative to future sales growth in the US.

Based on the data provided in table, which of the following statements is a valid conclusion about sales of beers?

- If the forecasted trends continue, sales from emerging markets will be greater than those in developed markets outside North America in 20 years from now;

- Looking at the past four years, the emerging markets have grown faster in terms of sales compared to the rest of the world;

- Sales in emerging markets are expected to grow three times quicker in the next ten years than they have grown in the previous four years;

- Four years ago, sales in emerging markets represented less than 10% of total global beer sales.

Which of the following statements, if true, best explains why future trends for North American beer sales differ from sales in other developed markets?

- North America will have the strongest growth of all countries in ale beers sales in the future;

- North America will have the strongest growth in homebrewing of all countries in the future;

- Developed markets outside North America will have the strongest increase in the number of people drinking beer in the future versus the other regions;

- Developed markets outside North America will have the most efficient beer production facilities in the future versus the other regions.

## Exercise 4

![bar_chart_visual](https://raw.githubusercontent.com/ZXVentures/code-challenge/master/files/images/bar_chart_visual.png)

Given the field list on the table below, reproduce the following chart in the fields:

Shared Axis dimensions: ____________

Column Values metrics: ____________

Line Values metrics: ____________

Filters metrics and dimensions: ____________

![table_visual](https://raw.githubusercontent.com/ZXVentures/code-challenge/master/files/images/table_visual.png)

Given the field list on the page below, reproduce the table in the fields:

Rows: ____________

Columns: ____________

Values: ____________

Filters: ____________

### Tables names and their fields

| Customer Dimension| Date Dimension| Product Dimension| Product Category Dimension| Product Subcategory Dimension| Internet Sales Fact|
|--------------------|--------------------|-------------------|----------------------------|-------------------------------|-----------------------|
| Customer Key| Date Key| Model Name| Product Category| Product Subcategory| Discount Amount|
| Yearly Income| English Month Name| Product Name||| Freight|
|| Fiscal Quarter|||| Order Date|
|| Fiscal Year|||| Order Quantity|
|||||| Product Standerd Cost|
|||||| Sales Amount|
|||||| Sales Order Number|
|||||| Tax Amount|
|||||| Total Product Cost|

## Exercise 5

Given the charts below build a dimensional model to represent the information

![charts](https://raw.githubusercontent.com/ZXVentures/code-challenge/master/files/images/charts.png)

## Exercise 6

![dimensional_model](https://raw.githubusercontent.com/ZXVentures/code-challenge/master/files/images/dimensional_model.png)

_* DateID field is a date datatype_

Given the dimensional model presented, build the following SQL queries:

- Returning the evolution of quantity in inventory per product category per date;

- Returning the most recent inventory position of quantity of products per category;

- Returning the quantity of distinct products that have ever been stored in each state
- Returning the last position of volume of products per month, and the average volume per product, per state and product of USA in 2017

## Exercise 7

Share two projects that you have developed that required complex ETL, explain the complexity and how you solved it

## Exercise 8

Draw a data flow for loading data from an e-Commerce site to a Data Mart. The data will be extracted from APIs and needs to be combined with data from Excel files before it is stored in the Data Mart - explain the main components and the tools you would use. Show how the end-users will access the data.