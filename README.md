# Amazon_Vine_Analysis

## Overview

The purpose of this challenge was to analyze the Amazon Vine Program to determine if there is a bias for favorable reviews from Vine members on video games in the US. To perform the analysis, we used PySpark for the ETL process then we connected to an AWS RDS instance to load the transformed data into PgAdmin tables.

## Results

### Total Number of Reviews:

The total number of reviews for the Vine Members on video games was 94:

 ![image](https://user-images.githubusercontent.com/78935982/123558973-f8713b00-d75e-11eb-853b-40da99771942.png)


The total number of reviews for the Non-Vine Members on video games was 40,471:

 ![image](https://user-images.githubusercontent.com/78935982/123558976-fc9d5880-d75e-11eb-9965-c75e9960dce7.png)


### Total Number of 5 Star Reviews:

The total number of Vine Member 5 Star Reviews on video games was 48:

 ![image](https://user-images.githubusercontent.com/78935982/123558980-01620c80-d75f-11eb-96d7-bb84f80fe2b7.png)


The total number of Non-Vine Member 5 Star Reviews on video games was 15,663:

 ![image](https://user-images.githubusercontent.com/78935982/123558981-04f59380-d75f-11eb-984b-f4629de8adae.png)


### Percent of 5 Star Ratings:

The percentage of 5 Star Reviews for Vine Members on video games was 51.06%:

 ![image](https://user-images.githubusercontent.com/78935982/123558984-09ba4780-d75f-11eb-85cb-6c5c2c6d2b45.png)


The percentage of 5 Star Reviews for Non-Vine Members on video games was 38.7%:

 ![image](https://user-images.githubusercontent.com/78935982/123558985-0d4dce80-d75f-11eb-89cb-facd8ce3a00f.png)


## Summary

In summary, I believe there is a bias towards more favorable or 5 Star ratings for video games when part of the Vine Program. The Vine Members had a 51% 5 Star Rating compared to the Non-Vine Members who had a 39% 5 Star Rating. Additionally, we could analyze the statistical distribution (mean, median and mode) of the star rating for the Vine Member and Non-Vine Member reviews.
