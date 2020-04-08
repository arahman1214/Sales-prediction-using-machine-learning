# Sales-prediction-using-supervised-machine-learning(Walmart weekly sales)
</br>

**Problem Statement**

You are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and you are tasked with predicting the department-wide sales for each store.
In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.
</br>
</br>
**stores.csv**

This file contains anonymized information about the 45 stores, indicating the type and size of store.
</br>
**train.csv**

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:
</br>
Store - the store number</br>
Dept - the department number</br>
Date - the week</br>
Weekly_Sales -  sales for the given department in the given store</br>
IsHoliday - whether the week is a special holiday week</br>

**test.csv**

This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

**features.csv**

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number</br>
Date - the week</br>
Temperature - average temperature in the region</br>
Fuel_Price - cost of fuel in the region</br>
MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.</br>
CPI - the consumer price index</br>
Unemployment - the unemployment rate</br>
IsHoliday - whether the week is a specialholiday week</br>
</br>
For convenience, the four holidays fall within the following weeks in the dataset (not all holidays are in the data):
</br>
Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13</br>
Labor Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13</br>
Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13</br>
Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13</br>



**Total we have 421570 values for training and 115064 for testing in train.csv and test.csv files repsctively**
**Our aim is to predict 6 months sales of walmart**
