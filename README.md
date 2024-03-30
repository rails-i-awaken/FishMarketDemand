# FishMarketDemand
Estimating Demand for Fish in SG's Wet Market

This project aims to estimate the demand function of fish by using data on fish sales at a particular wet mart. It aims to use knowledge learnt in fundamental economics together with a simple use case. 

#  Dataset Exploration
The dataset contains data on the price and quantity sold of fish in the wet market, which we would want to use for estimating the demand. This is given by the Log average daily prices of fish (per kg) and the Log average quantity sold of fish (in kg) in this wet market. 

It also contains other data items:
•	Day of the Week (Mon-Fri, Defined by dummy variables Mon, Tue, Wed, Thu)
•	Conditions at sea (Stormy [binary], Mixed [binary], Wind Speed [numerical])
•	Conditions at shore (Cold [binary], Rainy [binary])
•	Date [yymmdd]

In total, there are 111 observations from 1991-12-02 to 1992-05-08. 

#  Assumptions

1.	 Factors affecting the quantity demanded for fish:
a.	Day of the week: Shoppers may have different buying patterns over different days
b.	Conditions at shore (Cold, Rainy): Bad weather at shore could discourage customers to visit the market and hence decrease the quantity demanded for fish

2.	Factors not affecting the quantity demanded for fish:
a.	Conditions at sea (Stormy, Mixed, and Wind): Sea conditions do not impact customers' intentions to visit the market, and thus have no influence on their decisions to purchase fish.

3.	Demand for fish is a linear function of price. 

4.	Time series effects are assumed to be negligible for this dataset.
a.	Quantity sold has no correlation with time across the time period as shown

5.	Besides the variables in the dataset, there are no other significant variables affecting the quantity demanded for fish.


