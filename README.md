# Growth-Rate-Analysis
**By Azeez Adewale**
# Introduction:
 I decided to put my data analytics skill to practice so i got this dataset from kaggle, though the dataset seem to have very little information but for my analytical instinct, i was still able to draw insight from it.
# Project Goals: Problem Statement
To better understand the changes that occurred in the sales of products over a period one year.
This will help us to:
* Identify the state of the online store in terms of revenue.
* Come up with strategies to either maintain or improve the current State.

**Key Questions**
* What is the month on month sales revenue and growth rate?
* What is the quater on quater sales revenue and growth rate?
* Revenue forecast for the next one year.

# Data Source:
The data was sourced from kaggle, it is an online retail store data with over five hundred thousand rows and eight columns
InvoiceNo,	StockCode,	Description,	Quantity,	InvoiceDate,	UnitPrice,	CustomerID and	Country.

# Data Transformation:
Using excel i was able to remove all blank rows and unprintable descriptions, add a calculated column for revenue, new columns for the year, months by name and quaters by name. I also calculated the monthtly growth rate using the (Recent month - Previous month)/previous month * 100. 
Using the RRI excel function  i caculated the Compound Monthly Grow Rate (CMGR), which i used to forecast the revenue growth of the retail store for the next one year.

# Findings & Insights:

**Month On Month Sales Revenue And Growth Rate**
* The month on month chart shows a decrease and increase in sales revenue and growth rate. 
* Some of the months had negative growth rate.
<img width="1000" alt="monthonmonth" src="https://user-images.githubusercontent.com/108735886/186972725-caf1dbcb-d48a-4288-aaaa-f7c0f03a34c0.png">

**Quater On Quater Sales Revenue And Growth Rate**
* The quater on quater chart shows an increase in the sales revenue and growth rate.
<img width="1000" alt="QoQ" src="https://user-images.githubusercontent.com/108735886/186974517-4275d2b6-bb28-4816-9129-529fa7ea339d.png">

**Revenue Forecast For The Next Year**
* The revenue forecast chart shows a steady growth in the revenue month on month.
<img width="1000" alt="revenueforecast" src="https://user-images.githubusercontent.com/108735886/186974541-ec083a6b-22d0-4107-b462-9f4435715886.png">

# Analysis Summary
* The month on month chart shows a decrease and increase in sales revenue and growth rate. 
* Some of the months had negative growth rate.
* The quater on quater chart shows an increase in the sales revenue and growth rate.
* The revenue forecast chart shows a steady growth in the revenue month on month.
* The steady revenue growth in the forecast chart was possible because the compound monthly growth rate is positive. 

# Recommendations
* The store should consider a change in sales strategy, it should look into locations where there are
  more sales and look at products which brings high revenue.

* Marketing campaigns for the high selling products can be targeted at the top locations in these less performing months.

* Effort should be made to know how many customers purchase in these months are they repeat customers or new customers
  so as to work on customer retention programs.






