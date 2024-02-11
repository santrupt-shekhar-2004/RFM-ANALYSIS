
# RFM Analysis

# GOAL OF PROJECT:
The purpose of this project is to conduct a Customer Segmentation Analysis for an Automobile bike Company. Customer segmentation is performed by developing a RFM Model. RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach grouping customers into segments. It groups the customers on the basis of their previous purchase transactions. In this analysis the customer segment was divided into 11 groups. The analysis will help in determining which customers segments should be targeted in order to enhance sales revenue for the company.The data quality assessment and analysis is done using Python.
This multi-faceted approach combines the power of data visualization with advanced analytics to offer a holistic view of customer behavior and preferences.
By leveraging the insights derived from the RFM Model, the company can make informed decisions on resource allocation and tailor marketing campaigns to resonate with specific customer segments. Ultimately, this analysis serves as a strategic tool for enhancing overall business performance and maximizing sales potential within the competitive automotive bike market.

# Data Quality Assessment and Data Cleaning
In the data cleaning step the data quality of the following datasets were first assesed. After a data quality assessment the following data quality issues was observed and the necessary process to mitigate the issue was followed :

## 1) CustomerDemographics.xlsx :
* Irrelevent column was present and such columns were dropped from the dataset.
* There were 5 columns were Missing values were present. Such columns were dropped.
* For gender column there was no standardisation of data. Based on the values available the column data was standardised to remove data inconsistency.
* The Date of Birth column was transformed to create a new feature column 'Age' and 'Age Group' to check for discripency of age distribution. An outlier was observed and  the  record was removed.
*Checked whether there are duplicate records present in the dataset. In this dataset there were no duplicate records.
## 2)NewCustomerList.xlsx :
* 5 Irrelevent column was present and such columns were dropped from the dataset.
* There were 4 columns were Missing values were present. For such columns based on the volumne of the missing values either the records were dropped or appropiate values  were imputed at places of missing values
* The Date of Birth column was transformed to create a new feature column 'Age' and 'Age Group' to check for discripency of age distribution.
* There was no data inconsistency.
## 3)Transaction_data.xlsx :
* The product_first_sold_date column is not in datetime format. The data type of this column was changed from int64 to datetime format.
* There were 7 columns were Missing values were present. For such columns based on the volumne of the missing values either the records were dropped or appropiate values  were imputed at places of missing values
* A new feature column 'Profit' was created which is basically the difference between list price and standard price.
## 4)CustomerAddress.xlsx :
* For states column there was no standardisation of data. Based on the values available the column data was standardised to remove data inconsistency.
* There were certain customer IDs from Customer Dempgraphics table which were getting dropped in the Address table.

# Exploratory Data Analysis 
## 1)New vs Old Customers Age Distribution
![Image 11-02-24 at 12 52 PM (1)](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/61466861-a15f-4a16-b120-477aed0759ae)![Image 11-02-24 at 12 52 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/cf31162b-07ed-4a64-8ce2-88cd13edcff5)

* Most New customers are aged between 40-49 also for Old Customers the most of them are aged between 50-59
* The lowest number of customers for both the types of customers is present in the age bracket under 20 and above 80 age groups.
## 2)Bike purchases over last 3 years by Gender
![Image 11-02-24 at 1 07 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/0e8a2271-8763-40cc-8252-4d302117b10e)
* Most bike puechases are done by Feamale over the last 3 years. Approximately 51% of the bike purchases are done by Female compared to 49% of the purchases being done by Male.
## 3)New vs Old Customers Job Industry Distribution
![Image 11-02-24 at 1 11 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/a1ab2c90-3c1c-4529-8707-b85ba4ada3ea)![Image 11-02-24 at 1 11 PM (1)](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/68b655c0-4ec5-4624-b975-3501b06698bd)
* Most New customers are from the Manufacturing and Financial Services sector. Simillar trend is observed under old customers.
* The lowest number of customers are from the Agriculture and Telecom sector

## 4)Wealth Segmentation by Age Category
![Image 11-02-24 at 1 20 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/8400d558-9866-40de-9842-52765c4ad270)
![Image 11-02-24 at 1 20 PM (1)](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/8508ee21-8155-4925-a195-3db12431e911)
* Across all age categories the largest number of customers are from 'Mass Customer' Segment

## 5)Cars owned by States

![Image 11-02-24 at 1 23 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/f02aa828-1bf0-4e9c-bfea-0929565286dd)
* New South Wales has the largest number of people who donot own a car.

# Customer Segmentation
The RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach grouping customers into segments. It groups the customers on the basis of their previous purchase transactions.
In this analysis the customer segment was divided into 11 groups :
* Platinum Customers
* Very Loyal Customers
* Recent Customers
*Potential Customers
* Lost Customers
* Losing Customers
* Late Bloomer
* High Risk Customers
* Evasive Customers
* Becoming Loyal
* Almost lost Customers
![Image 11-02-24 at 1 33 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/beee827e-f6b4-4c74-92ea-07de6f0f6068)

# RFM Analysis: Scatter Plots

## Recency vs Monetary :

The visualization shows that recent customers have purchased more products and generated relatively more revenue.
  
![Image 11-02-24 at 1 42 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/f8fd5bcf-2987-4dcc-8b84-11269212bfa7)

## Frequency vs Monetary :
The visualization shows that customers belonging to Platinum, Very Loyal and Becoming Loyal Customer Segments have a greater frequency thus generate greater monetary.
![Image 11-02-24 at 1 48 PM](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/80c1bf96-c3be-493c-9272-2aecb5b65898)






## Documentation

[Documentation](https://linktodocumentation)


# Hi, I'm Santrupt Shekhar! 👋
- [@santrupt-shekhar-2004](https://github.com/santrupt-shekhar-2004)



## 🛠 Skills
Python, C++, Data Analytics, Web Scraping

