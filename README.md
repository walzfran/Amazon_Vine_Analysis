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
##### When looking at these results, it shows that there is not a positivity bias with Vine reviews for Beauty Products having higher star ratings as our data shows that there is a higher percentage of 5 star reviews coming from non-Vine reviews. One thing I thought was interesting was looking at the number of helpful votes. Below are two images the first showing the helpful votes from Vine reviews and the second showing helpful votes from non-Vine reviews. 

![Image_6](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/Helpful_Vine.png)
![Image_7](https://github.com/walzfran/Amazon_Vine_Analysis/blob/main/Images/Helpful_non-vine.png)

##### There are far more "Helpful Votes" when it comes to the Vine reviews, this might mean that the reviews are more helpful meaning they may contain more information, they may also have a bit more criticism in the reviews which would result in a smaller percentage of 5 star reviews. While having a Vine review for your product may not mean you will have higher stars you may have more accurate reviews. These Vine reviews are also coming from people who may be more versed in reviewing similar products, they know what to look for in the products and different methods of testing them such as a face foundation, a professional reviewer who is familiar with beauty products would know what to look for like coverage types and formulation of the products ingredients. I know that when I am looking to purchase a new product, especailly one that I am going to use on myself I want to have trusted reviews and it does make me feel more confident in a product review when there are more "helpful" votes as it shows me that other people in my shoes felt that these reviews were valid and assisted them in the decision making process. 

##### If I were to take this analysis further I would change the amount of total votes to 50 or more instead of the 20. This way we can really look at reviews that were more useful to the consumer, I would also open up the star rating to include 4 stars, the reason being that for a product to be great it does not need 5 stars, sometimes it is helpful to look at 4 star reviews as well because they can show a bit more critique of the product so you can know a bit more about your potential purchase. 

