# REDOX-Airlines

### AirPlane Analysis

![](Raydox_frontpage.jpg)

## Introduction

This Excel project aims to provide insights into the performance of REDOX Airlines company over the years. By analzing various aspects of the data, we seek to reduce redundance, identify sales trends, monitor the Aircraft through tracking and monitoring of KPIS and make data driven recommendations to drive the business growth and position in the industry.

## Objective
Here are ideas of how these reports will be used:

- To create Pivot Tables and Pivot Charts.
- To analyze the data and present key insights to drive the business growth.   
- To give actionable recommendation.

## Data Sources
The Primary dataset used for this project is the Flights data, Aircraft data, Routes data and Airports data containing detailed information about the revenue made, routes and aircraft of the company.

## Problem statement/ Requirement.

The airline's management team has a strong airline operations background, but the current data setup is messy and inefficient. Getting specific aircraft details such as route and seating capacity requires comparing multiple files, slowing down operations. This disjointed system prevents quick and informed decision-making. For a start, a couple of numbers have been identified to be reported in their data as reports.

A one page dashboard
Case 1
  - How many flights use the A319 aircraft?
  - What is the most common type of aircraft across all flights?
  - What is the maximum average ticket price for flights on the A320 aircraft?

Case 2
  - Show the fuel cost per mile in Dollars (hint: Aircraft table)
  - Show the total revenue per flight, assuming a 10% tax on all fares (hint:Flights table)

Case 3
  - Where are we losing the most money?

Case 4
  - Where are we most profitable?

Case 5
  - How many flights are flown from O'Hare (ORD) to Los Angeles International Airport (LAX)?

Case 6
  - Which route accounts for the lowest percentage of total revenue?

Case 7
  - What was the most popular month to fly to Fort Lauderdale (FLL)?

Case 8
  - Create a visual representation to show the number of flights per month on the ORD-PHL route

Skills/ Concepts demonstrated:
-  Excel advance formulas(Sum, INDEX MATCH, Multiplication, TEXT)
-  Pivot Tables
-  Pivot Charts

## Data Cleaning and Transformation 
Four dataset was provided for this project which are the **_Flights data_**, **_Aircraft data_**, **_Routes data_** and **_Airports data_**. The following data cleaning was done on the dataset as this will help in getting accurate results for our visualisation. 

Understanding the dataset first was a crusial part of this project and the following cleaning was done.
-  Data type was changed
-  The four dataset was merged as one using the INDEX MATCH excel formula to form a single dataset.
-  A new column was created to get the day name of the week.

## Modelling:
The best type of model in power Bi is the star schema, an automatically derived dimension table was adjusted to remove and replace unwanted relationship.

![](Reydox_Table.Png)

The model is a star schema.
There are 5 dimenstion tables and 2 fact tables. The dimension tables are all joined to the fact tables with one-to-many- relationship.

## Visualization:

The report comprises of 3 pages:
1.  Sales Overview
2.  Marketing Performance
3.  Insights and Recommendations

You can interact with the dashboard  
[here](https://app.powerbi.com/view?r=eyJrIjoiODRlMGZhM2UtM2MzYi00ZjYxLTgwNGMtZDMxYmZmYjU4NzdkIiwidCI6IjUwODUxMjk2LTliZDEtNGM1Yi05MDllLWY2M2U0OWVmZWEyNSJ9)

## Analysis:

Here, we could discover the following insights.

## Sales Overview: 

![](SalesOverview.png)

- The Total Revenue was $11.12bn
- The total Target was $8.45bn
- The Revenue YTD was $2.66bn against the Target YTD of $2.43.
- Pharmacy Channel generated a total of 52.9% revenue  higher than Hospital 47.1% revenue.

## Marketing Performance:

![](Marketing.png)

-  There are 240 products.
-  Each product price cost $412.57 on average.

## Recommendation
-  It's positive that the total revenue from 2022-2025 exceeded the target revenue, indicating overall success.
-  Identify underperforming products and develop strategies for improvement.
-  Assess why the Pharmacy Channel outperformed the Hospital Channel. Identify strategies from the Pharmacy Channel that can be implemented in the Hospital Channel to boost revenue.

You can connect with me ![here](https://www.linkedin.com/in/victoriaogwuche/)

![](thankyou.png)
