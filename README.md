# Amazon_Vine_Analysis

## Overview of the Analysis
PySpark, AWS, and Postgres were used to analyze Amazon reviews for Office Products to determine if reviews from Amazon Vine members are biased. The Office Products dataset was chosen from Amazon and an analysis was conducted using PySpark to perform the ETL process, connect to an AWS RDS instance, and to load the transformed data into pgAdmin. PySpark was also used to analyze the dataset and determine the bias towards favorable reviews from Amazon Vine members.



## Results : 

### Perform ETL on Amazon Product Reviews

![Customer_table](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/2.png)

![DB - Customer Count](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/7.png)

![Products table](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/3.png)
![DB - Products Count](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/8.png)

![Reviews table](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/4.png)

![DB - Review](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/6.png)

![Vine table](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/5.png)

![DB - Vine](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/9.png)


### The Amazon Office Products Reviews dataframe has

* 969 reviews were from Amazon Vine members

* 43,745 reviews were not from Amazon Vine members

* Of the 969 reviews from Amazon Vine members, there were 430 5-star reviews

* Of the 43,745 reviews not from Amazon Vine members, there were 19 5-star reviews

* 44% of reviews by Amazon Vine members were 5 stars

* 44% of reviews not by Amazon Vine members were 5 stars

![Reviews Screen Shot](https://github.com/raajasrini/Amazon_Vine_Analysis/blob/main/images/d25.png)

## Summary :
Comparing the percentage of reviews that were 5 stars from both Amazon Vine members and not Amazon Vine members, it can be concluded that there is no positivity bias for reviews of Office Products in the Vine program. The percentage of five-star reviews from both groups are nearly the same, rounded to 44%. A similar analysis could be conducted to compare the one-star or low reviews from both Vine and non-Vine members to further support this conclusion.


