# TABLEAU
# 1- Marketing Performance Report

## Overview
This project contains a **Marketing Performance report** designed to analyze customer purchasing behavior and engagement metrics. The goal of this report is to provide insights on customer demographics, spending patterns, and response to marketing campaigns, helping stakeholders make data-driven decisions.

includes visualizations of key performance indicators such as sales amounts, product categories, number of visits, and campaign responses.

![Marketing Performance Dashboard]("Marketing_Performance/Marketing Performance.png")

## Data Description
---

## marketing_data.csv

| Column           | Sample Value   | Interpretation |
|-----------------|----------------|----------------|
| ID               | 5642           | Unique customer ID |
| Year_Birth       | 1980           | Customer’s year of birth |
| Education        | Master         | Educational qualification of the customer |
| Marital_Status   | Together       | Customer’s marital status |
| Income           | $62,499.00     | Customer’s annual income |
| Kidhome          | 1              | Number of kids the customer has |
| Teenhome         | 1              | Number of teenagers the customer has |
| Dt_Customer      | 12/09/2013     | Date of customer registration with the company |
| Recency          | 99             | Number of days since customer’s last purchase |
| AmtLiq           | 140            | Amount spent on alcoholic beverages |
| AmtVege          | 4              | Amount spent on vegetables |
| AmtNonVeg        | 61             | Amount spent on meat items |
| AmtPes           | 25             | Amount spent on fish products |
| AmtChocolates    | 30             | Amount spent on chocolates |
| AmtComm          | 197            | Amount spent on commodities |
| NumDeals         | 2              | Number of deals purchased with a discount |
| NumWebBuy        | 3              | Number of purchases made from the website |
| NumWalkinPur     | 6              | Number of in-store purchases |
| NumVisits        | 4              | Number of website visits per month |
| Response         | 1              | Boolean. 1 if the customer accepted the last campaign’s offer, 0 otherwise |
| Complain         | 1              | Boolean. 1 if the customer had complained in the last 2 years, 0 otherwise |
| Country          | SP             | Customer’s location (AUS = Australia, CA = Canada, GER = Germany, IND = India, ME = Montenegro, SA = South Africa, SP = Spain, US = United States) |
| Count_success    | 1              | Total number of successful lead conversions |

---

## ad_data.csv

| Column           | Sample Value   | Interpretation |
|-----------------|----------------|----------------|
| ID               | 5642           | Unique customer ID |
| Bulkmail_ad      | 1              | Boolean. 1 if the customer converted successfully from a bulk e-mail campaign, 0 otherwise |
| Twitter_ad       | 1              | Boolean. 1 if the customer converted successfully from a Twitter ad, 0 otherwise |
| Instagram_ad     | 1              | Boolean. 1 if the customer converted successfully from an Instagram ad, 0 otherwise |
| Facebook_ad      | 1              | Boolean. 1 if the customer converted successfully from a Facebook ad, 0 otherwise |
| Brochure_ad      | 1              | Boolean. 1 if the customer converted successfully from a company brochure, 0 otherwise |

---
