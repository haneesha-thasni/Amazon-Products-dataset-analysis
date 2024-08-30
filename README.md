# Amazon-Products-dataset-analysis

![image](https://github.com/user-attachments/assets/8a47e3ba-e9ef-4331-ba0d-14bb04c5d295)

An Amazon product dataset typically includes a wide range of information about products sold on Amazon's platform. The exact structure and content can vary depending on the specific dataset, but here are some common fields you might find:

## Dataset Description: Amazon Product Data

* Unnamed: 0: An index column that may have been automatically generated when the dataset was imported into a DataFrame. It typically serves as a row identifier.

* asin: The Amazon Standard Identification Number (ASIN), a unique identifier assigned to each product on Amazon.

* product_title: The name or title of the product as listed on Amazon.

* product_price: The current selling price of the product on Amazon.

* product_original_price: The original price of the product before any discounts, sales, or promotions were applied.

* currency: The currency in which the product price is listed (e.g., USD, EUR).

* product_star_rating: The average star rating of the product, typically on a scale of 1 to 5 stars, as rated by customers.

* product_num_ratings: The total number of customer ratings that the product has received.

* product_url: The URL link to the product's detail page on Amazon.

* product_photo: The URL link to the product's image or photo on Amazon.

* product_num_offers: The number of different offers available for the product, possibly from various sellers or different conditions (e.g., new, used).

* product_minimum_offer_price: The lowest price among all available offers for the product.

* is_best_seller: A binary indicator (e.g., 0 or 1) that shows whether the product is a best seller in its category on Amazon.

* is_amazon_choice: A binary indicator that signifies whether the product is an "Amazon's Choice" item, a label given to highly-rated, well-priced products available for quick shipping.

* is_prime: A binary indicator showing whether the product is eligible for Amazon Prime benefits, such as free two-day shipping.

* climate_pledge_friendly: A binary indicator showing whether the product is part of the "Climate Pledge Friendly" initiative, indicating that it meets certain sustainability standards.

* sales_volume: The volume of sales for the product, which may represent the number of units sold or total sales in monetary terms.

* delivery: Information about the delivery options, times, or availability for the product.

* has_variations: A binary indicator showing whether the product has variations, such as different sizes, colors, or models available.

* product_availability: The availability status of the product (e.g., in stock, out of stock, pre-order).

* unit_price: The price per unit of the product, useful for items sold in bulk or packages.

* unit_count: The number of units included in the product package or the total quantity of the product.

This dataset can be used for a variety of analyses, such as examining product pricing trends, identifying best sellers, analyzing customer ratings and reviews, and more. It's a rich source of information that can help understand market trends, consumer behavior, and product performance on Amazon.

## Information about the dataset

- This dataset contains detailed information about 64 Amazon products, captured in 22 columns. Each entry represents a 
   unique product, including data on pricing, ratings, availability, and various product features.

- The dataset contains several columns with varying numbers of null values:-
    * product_original_price: This column has 37 null values, suggesting that for 37 products, the original price was not 
      available or not applicable.
    * product_star_rating: There are 10 null values, implying that 10 products do not have a star rating, possibly due to a 
      lack of reviews.
    * sales_volume: This column has 3 null values, suggesting that sales volume data is missing for 3 products.
    * delivery: There is 1 null value, indicating that delivery information is missing for 1 product.
    * product_availability: This column has 46 null values, indicating that the availability status is missing for 46 
      products.
    * unit_price: There are 59 null values, meaning the unit price is missing for 59 products.
    * unit_count: This column also has 59 null values, suggesting that the unit count is missing for the same 59 products.

- The dataset includes both numeric and categorical data types.
  
- Several columns have missing values, particularly product_original_price, product_star_rating, product_availability, 
   unit_price, and unit_count.

The dataset provides insights into product pricing, availability, customer feedback, and more, making it useful for 
various analytical tasks, including price comparison, market analysis, and customer sentiment analysis.
This dataset can be used for data analysis, visualization, and machine learning projects related to e-commerce.

## Questions 

FILTERING QUESTIONS:

1. get the details with product 's star rating 4.0 and above
2. identify products that are best sellers
3. select products labeled as amazon's choice
4. identify the product details with currency is USD
5. to get only the products that are listed as "Only 7 left in stock - order soon"?
6. to get only the products that have a star rating of 4.5 or higher and are eligible for Amazon Prime?
7. to get only the products that have a star rating of 3.0 or higher and are listed as "Only 7 left in stock - order soon"?
8. Filter the data to get the products that have "5G" in their product title?

SORTING QUESTIONS:

1. sort in descending order based on the product_star_rating column?
2. Sort products alphabetically by their title.
3. Sort by star rating in descending order and then by price in ascending order
