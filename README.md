
# RFM Analysis

# GOAL OF PROJECT:
The purpose of this project is to conduct a Customer Segmentation Analysis for an Automobile bike Company. Customer segmentation is performed by developing a RFM Model. RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach grouping customers into segments. It groups the customers on the basis of their previous purchase transactions. In this analysis the customer segment was divided into 11 groups. The analysis will help in determining which customers segments should be targeted in order to enhance sales revenue for the company.The data quality assessment and analysis is done using Python.
This multi-faceted approach combines the power of data visualization with advanced analytics to offer a holistic view of customer behavior and preferences.
By leveraging the insights derived from the RFM Model, the company can make informed decisions on resource allocation and tailor marketing campaigns to resonate with specific customer segments. Ultimately, this analysis serves as a strategic tool for enhancing overall business performance and maximizing sales potential within the competitive automotive bike market.

# Data Quality Assessment and Data Cleaning
In the data cleaning step the data quality of the following datasets were first assesed. After a data quality assessment the following data quality issues was observed and the necessary process to mitigate the issue was followed :

1) CustomerDemographics.xlsx :
-1 Irrelevent column was present and such columns were dropped from the dataset.
-There were 5 columns were Missing values were present. Such columns were dropped.
-For gender column there was no standardisation of data. Based on the values available the column data was standardised to remove data inconsistency.
-The Date of Birth column was transformed to create a new feature column 'Age' and 'Age Group' to check for discripency of age distribution. An outlier was observed and  the record was removed.
-Checked whether there are duplicate records present in the dataset. In this dataset there were no duplicate records.
2)NewCustomerList.xlsx :
-5 Irrelevent column was present and such columns were dropped from the dataset.
-There were 4 columns were Missing values were present. For such columns based on the volumne of the missing values either the records were dropped or appropiate values  were imputed at places of missing values
-The Date of Birth column was transformed to create a new feature column 'Age' and 'Age Group' to check for discripency of age distribution.
-There was no data inconsistency.
3)Transaction_data.xlsx :
-The product_first_sold_date column is not in datetime format. The data type of this column was changed from int64 to datetime format.
-There were 7 columns were Missing values were present. For such columns based on the volumne of the missing values either the records were dropped or appropiate values  were imputed at places of missing values
-A new feature column 'Profit' was created which is basically the difference between list price and standard price.
4)CustomerAddress.xlsx :
-For states column there was no standardisation of data. Based on the values available the column data was standardised to remove data inconsistency.
-There were certain customer IDs from Customer Dempgraphics table which were getting dropped in the Address table.

# Exploratory Data Analysis 
![Image 11-02-24 at 12 52 PM (1)](https://github.com/santrupt-shekhar-2004/RFM-ANALYSIS/assets/114929801/61466861-a15f-4a16-b120-477aed0759ae)


- [@santrupt-shekhar-2004](https://github.com/santrupt-shekhar-2004)



## Documentation

[Documentation](https://linktodocumentation)


# Hi, I'm Santrupt Shekhar! 👋



## 🛠 Skills
Python, C++, Data Analytics, Web Scraping

