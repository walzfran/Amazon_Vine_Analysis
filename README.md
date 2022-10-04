# Amazon_Vine_Analysis
![Image_1](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/Vine-Header.png)

#### Overview of the Analysis
##### The purpose of my Amazon Vine Analysis is to use PySpark to perform the ETL process and extract information from a dataset of Amazon reviews. The dataset contained both paid and unpaid reviews and we are going to look at the breakdown of them. To accomplish this task I connected the AWS RDS and linked it to PGAdmin and then used PySpark to determine if there was bias towards Vine member reveiws. 

###### Below is an image showing the the datasets were successful uploading information to PGAdmin 
![Image_2](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/ETL_added_PGADMIN.png)

###### Here are two additional screenshots taken from PGAdmin showing the select function
![Image_3](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/customers_table.png)
![Image_4](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/product_table.png)

#### Results of the Analysis

![Image_5](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/pyspark_totals.png)

##### * How many Vine reviews and non-Vine reviews were there?
##### As the image above shows, there are 647 Vine reveiws and 74,113 non-Vine reviews

##### * How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
##### As the image above shows, there are 229 reviews with 5 stars coming from Vine reveiws and 43,217 reviews with 5 stars coming from non-Vine reviews

##### * What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
##### As the image above shows, the percentage of 5 star reviews from Vine reviews is 35.4% and the percentage of 5 star reviews from non-Vine reveiws is 58.3%

#### Summary 
##### 

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.


