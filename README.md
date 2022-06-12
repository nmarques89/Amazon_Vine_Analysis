# Amazon_Vine_Analysis
## Overview of Project
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark, in this case operated through ther Google Collaborate platform, to undertake the ETL process to extract the dataset, transform the data, connect to an Amazon Web Services(AWS) RDS instance, and load the transformed data into pgAdmin for the purposes of calculating different metrics.
I focused on video game reviews in the United States

### Initial PgAdmin Tables
Customers Table

![Customers_SQL](https://user-images.githubusercontent.com/99096376/173248367-0029c947-66fd-442a-8ea0-8549781dd6bf.png)

Products Table

![Prodcuts_SQL](https://user-images.githubusercontent.com/99096376/173248383-0e5ad8ff-88bd-47fe-9167-b4b0ddcdcaf0.png)

Review Id Table

![Review_ID_Postgres](https://user-images.githubusercontent.com/99096376/173248403-9cc409fd-eca0-4a89-a269-3d4dc3ad04ee.png)

Vine Table

![Vine_Table_SQL](https://user-images.githubusercontent.com/99096376/173248416-f70d0313-655d-466d-a0c2-2be5c2eff097.png)

## Results of the Vine Program

Raw Data

![vine_results](https://user-images.githubusercontent.com/99096376/173248481-559c41a0-1078-4341-8e5c-392f529ec831.png)

### Summary of Results
1. The Amazon Vine Program is miniscule in its scope. At just 94 total reviews, the program represents .0023% of unpaid reviews
2. Nevertheless, paid 5 Star reviews represented 51& of all reviews, as opposed to 38.7% for unpaid reviews.
3. We can conclude that the Vine Program elicits a positivity Bias
4. Given the size and discrepancy of both participants and positive reviews, it is obvious that the vine program is not an accurate model and that unpaid reviews offer a more accurate, if dissappointing reality. 
