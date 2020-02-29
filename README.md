# Sales-prediction-using-supervised-machine-learning

Machine learning project for predicting weekly sales of walmart.

This problem consists of historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and the task is predicting the department-wide sales for each store.
In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.</br>
                                            The data collected ranges from 2010 to 2012, where 45 Walmart stores across the country were included in this analysis. Each store contains several departments, and we are tasked with predicting the department-wide sales for each store. It is important to note that we also have external data available like CPI, Unemployment Rate and Fuel Prices in the region of each store which, hopefully, helps us to make a more detailed analysis.</br>
                                            
**DataSet Overview**
This data set is available on the kaggle website. These data sets contained information about the stores, departments, temperature, unemployment, CPI, isHoliday, and MarkDowns.</br>
**Stores** :
Store: The store number. Range from 1–45.
Type: Three types of stores ‘A’, ‘B’ or ‘C’.
Size: Sets the size of a Store would be calculated by the no. of products available in the particular store ranging from 34,000 to 210,000.</br>
**Features:**
Temperature: Temperature of the region during that week.
Fuel_Price: Fuel Price in that region during that week.
MarkDown1:5 : Represents the Type of markdown and what quantity was available during that week.
CPI: Consumer Price Index during that week.
Unemployment: The unemployment rate during that week in the region of the store.</br>
**Sales:**
Date: The date of the week where this observation was taken.
Weekly_Sales: The sales recorded during that Week.
Dept: One of 1–99 that shows the department.
IsHoliday: a Boolean value representing a holiday week or not.
<br/>

**Total we have 421570 values for training and 115064 for testing. **
