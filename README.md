# Amazon Vine Analysis

## Project Overview

This project analyzes the Amazon Vine program to determine if paid reviews have a more favorable bias. PySpark is used to extract, transform, and load the data into SQL tables using PGAdmin. The analysis was focused on sports products.

## Results

### Vine Reviews
<p align="center">
  <img width="450" src="https://github.com/skgolden13/Amazon_Vine_Analysis/blob/main/Vine_Reviews.PNG"> <br/>
  Figure 1: Total Number of Vine Reviews <br/>
</p>

<p align="center">
  <img width="450" src="https://github.com/skgolden13/Amazon_Vine_Analysis/blob/main/5_Star_Vine.PNG"> <br/>
  Figure 2: Total Number 5 Star of Vine Reviews <br/>
</p>

<p align="center">
  <img width="450" src="https://github.com/skgolden13/Amazon_Vine_Analysis/blob/main/Vine_Percentage.PNG"> <br/>
  Figure 3: Percentage of 5 Star Vine Reviews <br/>
</p>

### Non-Vine Reviews
<p align="center">
  <img width="450" src="https://github.com/skgolden13/Amazon_Vine_Analysis/blob/main/Unpaid_Reviews.PNG"> <br/>
  Figure 4: Total Number of Non-Vine Reviews <br/>
</p>

<p align="center">
  <img width="450" src="https://github.com/skgolden13/Amazon_Vine_Analysis/blob/main/5_Star_Unpaid.PNG"> <br/>
  Figure 5: Total Number 5 Star of Non-Vine Reviews <br/>
</p>

<p align="center">
  <img width="450" src="https://github.com/skgolden13/Amazon_Vine_Analysis/blob/main/Unpaid_Percentage.PNG"> <br/>
  Figure 6: Percentage of 5 Star Non-Vine Reviews <br/>
</p>

## Summary
41.6% of Vine reviews were 5 star compared to 53.0% of Non-Vine reviews. The small sample size of vine reviews could be skewing the data set for sports products. An analysis across multiple product categories would be able to give a better representation of vine reviews.
