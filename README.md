# Growth-Rate-Analysis
**By Azeez Adewale**
# Introduction:
 I decided to put my data analytics skill to practice so i got this dataset from kaggle, though the dataset seem to have very little information but for my analytical instinct, i was still able to draw insight from it.
# Project Goals: Problem Statement
To better understand the changes that occurred in the sales of products over a period one year.
This will help us to:
* Identify what the state of the online store is in terms of revenue.
* Come up with strategies to either maintain or improve the current State.

**Key Questions**
* What is the month on month sales revenue and growth rate?
* What is the quater on quater sales revenue and growth rate?
* Revenue forecast for the next one year.

# Data Source:
The data was sourced from kaggle, it is an online retail store data with over five hundred thousand rows and eight columns
InvoiceNo,	StockCode,	Description,	Quantity,	InvoiceDate,	UnitPrice,	CustomerID and	Country.

# Data Transformation:
Using excel i was able to remove all blank rows and unprintable descriptions, add a calculated column for revenue, new columns for the year, months by name and Qauters by name. I also calculated the monthtly growth rate using the (Recent month - Previous month)/previous month * 100. 
Using the RRI excel function  i caculated the Compound Monthly Grow Rate (CMGR) which i used to forecast the revenue growth of the reatail store for the next one year.

# Findings & Insights:

**Month On Month Sales Revenue And Growth Rate**

<img width="576" alt="monthonmonth" src="https://user-images.githubusercontent.com/108735886/186972725-caf1dbcb-d48a-4288-aaaa-f7c0f03a34c0.png">
* The month on month chart shows a decrease and increase in sales revenue and growth rate. 
* Some of the months had negative growth rate.




**Quater On Quater Sales Revenue And Growth Rate**

<img width="576" alt="QoQ" src="https://user-images.githubusercontent.com/108735886/186974517-4275d2b6-bb28-4816-9129-529fa7ea339d.png">
* The quater on quater chart shows an increase in the sales revenue and growth rate.



**Revenue Forecast For The Next Year**

<img width="576" alt="revenueforecast" src="https://user-images.githubusercontent.com/108735886/186974541-ec083a6b-22d0-4107-b462-9f4435715886.png">
* The revenue forecast chart shows a steady growth in the revenue month on month.





