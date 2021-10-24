## Flight Price Expectation 

The goal of this project is to predict the price of flight from deferent locations to Riyadh in January 2022. Using Selenium, 3789 rows and 12 columns have been scraped from Almosafer.com for 11 different countries of Europe which represent the dataset. The 12 columns are the feature that will affect the price, such as the flight duration, time of landing and arriving, wight of the baggage and day of month.
!![image](https://user-images.githubusercontent.com/36573740/138600454-c2386d57-3ade-4ff0-a1e5-bf5c39a48844.png)



The figure above, is to represent the relation between the day of week and the average price for the Economy and Business class. the figure shows that is the highest flight prices will be in the Saturday because it is common weekend in Europe and Saudi Arabia  

Also, the figure represent that the flight prices decrease  in Monday (weekday)  so these days will effect on the price and make big change 
The result from the above figure is not enough to start building regression modules, in other word, the numerical values need to be increased, such as, number of stops. Also, the days should be divided into weekday and weekend. The next step will be creating extra numerical features then clean the dataset by removing outliers, nulls and duplicate. After that, different regression models will be built starting from linear regression, polynomial regression with different degrees, ridge regression, lasso regression and elastic regression, to decide with one is the best in term of R^2.
