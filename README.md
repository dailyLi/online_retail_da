# General Analysis into Online Retail Orders

## Objective
Due to the limited number of attributes, I only performed basic statistical analysis and applied association rules to discover business insights for this online retailer.

## Data
This analysis is based on a public data set from an anonymous online retailer in UK, which contains order transactions from 2010 to 2011. 
https://www.kaggle.com/rupakroy/online-retail?select=Online_Retail.csv

## Key findings

- Sales in November
highest revenue achieved by largest number of customers but with lowest ATV. 
It might be ascribed to marketing campaigns and promotions for holiday season.

- Association Rule
In general there are not siginificant evidence of products that are commonly purchased together. 
Looking into each country, one finding is in France that RED SPOTTY PAPER PLATES and CUPS, PLASTERS IN TIN series were usually purchased together
items in one series should be shown in groups and prompted for upsales whenever and wherever possible

## Suggestions on operation practice
from data quality perspective:

- Create seperate fields for product name and transaction description
- Try not to change product name too often
- Create another field for transaction category: whether it's regular customer transaction, large 2B order, bank transaction, restock, etc.
- Find another way to record and report mistakes and errors
- There might be database or information system design problems that prevent employees from complying to SOP, given the fact that there are 572 entries labeled as "MANUAL" with high unit price but no further explanations
