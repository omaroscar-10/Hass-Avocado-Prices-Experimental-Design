# Hass-Avocado-Prices-Experimental-Design-
Determine which price point (average price of avocado) will maximize the total amount of avocados sold.

# Introduction
According to the Hass Avocado Board 2019 Annual Report, demand remained relatively flat in 2019. Since there is a need to build demand; the goal of this experiment is to determine which price point (average price of avocado) will maximize the total amount of avocados sold.

Price is one of the economic factors that most affect the demand for consumer goods. As a result, the price of avocado will impact consumer spending on the fruit significantly since an increase in price will decrease the quantity of avocado demanded and viceversa.

That is, higher prices on avocados will deter spending and consumption; whereas low prices will increase consumption making it more likely that consumers will spend money on the product.

Therefore, this experiment will focus on comparing the difference in average price of avocado in the US in order to quantify consumption and spending.

# Hypothesis
Ho: There is no significant difference in the total volume of avocados sold between average price A and B.

Ha: There is a significant difference in the total volume of avocados sold between average price A and B.

# Data
This dataset was downloaded from Kaggle website (https://www.kaggle.com/neuromusic/avocado-prices).
The dataset represents weekly 2018 retail scan data for National retail volume (units) and price from 2015 to 2018. Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados. The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags. The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

In addition, the data contains 18249 rows and 14 columns. There are no null cells or missing values.

# Methodolody

Two average prices for organic and convetional avocados (prices A and B for organic and prices C and D for conventional) will be chosen for this analysis. These two pairs will be compared to determine which average price is effective to build demand and maximize the total volume of avocados sold.

>Organic Avocados prices A and B: 1.35 and 1.65 respecively.

>Conventional Avocados prices C and D: 0.9 and 1.15 respecively.

**Sample:** states will be chosen based on the Bureau of Economic Analysis which defines regions and categorize them by percent change in real GDP by state which serves for comparison of economic data.

**Hypothesis**: It is expected that average prices of 1.35 and 0.9 for organic and conventional avocados respectively will increase sales and consumer spending on the fruit.

**Outcome**: It is expected that demand for avocados total volume of sales will increase. In additon, revenue and amount of avocados sold will be used as key metrics to measure if the effectiveness of prices.

The methodology to analyze this experimeent will be the following:

First, split the data into daframes based on the types of avocado. Then plot the respective hitograms and calculate the descriptive statistics (skewness and kurtosis) to determine if the data is normally distribued. 

The histograms needs to roughly resemble a bell shape curve. 

The results of skewness need to fall within 3 and -3. Likewise, values of kurtosis need to fall within 8 and -8.

If the disribution is normal; t-test will be performed to verify if the means from the variables being tested are signficantly different. 

The t-test will return a test statistic and a p-value. The test statisic needs to be grater than 1.96 and the p-value needs to be greater than 0.05 to reject the null hypothesis.

If the data is not normally distributed; then the Krustal-Wallis will be performed to determine if the total volume of avocados sold differ meaningfully. 

The Kruskal-Wallis test returns a test statistic and a p-value. If the p-value is less than 0.05, then the null can be rejected because there would be a significant difference between the total volume avocados sold.

To determine whether there is a significant difference in the total volume of avocados sold between the chosen average prices (test the hypothesis); the experiment must be run, and data must be collected. However, there is no collected data since this is an experiment proposal; therefore, the average price from 2015 to 2018 will be examined to detect a difference in average price between those years which could possibly affect number of avocados sold.

# Results
Based on visual inspection and descriptive statistics the variable is normally distributed.

The null (that there is no significance in means) is rejected for the following pairs: 2015-2016, 2015-2017, 2016-2017, and 2017-2018; since their p-values are less han 0.05.

Finally, the 95% confidence interval and pointplot show that the average price of avocados sold in 2017 is significantly higher than 2015, 2016 and 2018.

# Discussion & recommendations
From this experiment, interested parties will be able to determine the following: whether the quantity demanded of avocado exhibits a large change in response to changes in its price; and which price point will maximize the total amount of avocados sold.

A sensitivity between avocados prices and demand means that a decrease in prices will result in higher demand, and an increase in demand will lead to an increase in supply. Therefore, producers will know if more avocados would need to be produced based on the price point to satisfy the demand. However, if there were to exist a weak price influence on demand; price will have a weaker impact on supply.

As a result, interested parties will be able to understand how supply or demand changes given changes in prices.

It is recommended to measure and track revenue. Buyers or consumers typically look for the lowest cost, while sellers look sell something for as much as possible. If price is too low, it would be impracticable for sellers since profits will be low. On the other hand, when prices become unreasonably high, buyers will change their preferences and move away from the product. Thus, it is important to find the proper balance (optimal price) whereby both buyers and sellers are able to benefit from the transaction.

# References
https://www.kaggle.com/neuromusic/avocado-prices
www.investopedia.com
