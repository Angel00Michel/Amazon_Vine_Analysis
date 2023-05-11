# Amazon_Vine_Analysis
Perform ETL on Amazon Product Reviews / Determine Bias of Vine Reviews

### Overview of the analysis
- Our purposef or this analysis is to extract one of the 50 datasets, transform the data, connect to an AWS RDS instance, and then load the transformed data into pgAdmin. 
- For reference, using PySpark determines if there is any bias toward favorable reviews from Vine members in the dataset and present a summary to the SellBy stakeholders.
- Using Google Colab offers explicit interpretation for all of these processes to run seamless. 

### Results
1. There were 613 paid Vine reviews, and 64,968 unpaid Vine reviews.
2. There were 222 "5 star" from paid Vine reviews, and 30,543 "5 stars" for non-Vine reviews.
3. 36.21% of Vine reviews were 5 stars. 47.01% of non-Vine reviews were 5 stars.

![image](https://github.com/Angel00Michel/Amazon_Vine_Analysis/assets/106771574/1d282d16-415e-43ce-a830-345a91a3eb4f)

### Summary
- There no positive bias for reviews in the Vine program since only 36.21% of Vine reviews were 5 stars. This applies for non Vine review as well as only 47.01% with a review of 5 stars. We can analyze all the reviews and find an average rating for Vine/Non-Vine users to give us more of an accurante representation of this model. 
