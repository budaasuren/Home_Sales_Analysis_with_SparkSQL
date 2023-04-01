# Home_Sales_Analysis_with_SparkSQL_and_PySpark

## Preprossing the data with PySpark

* Constructed the schema for the table and defined datatypes for each field using StructField form PySpark.
* Created new columns using year and withColumn functions.
* Found the average price for 4 bedrooms using Group BY function.

## Completed the EDA using SparkSQL
* Average price for 4 bedrooms by years.
* Average price for 3 bedrooms and 3 bathrooms by year built.
* Average price with multiple conditions by year.

## Executed The Comparision for the Different Scenarios
* The case with no caching and no parquet

![Screen Shot 2023-04-01 at 6 33 36 PM](https://user-images.githubusercontent.com/113545468/229318612-45eca44c-8b92-490d-801b-609826c7e85d.png)

* The case with caching

![Screen Shot 2023-04-01 at 6 35 17 PM](https://user-images.githubusercontent.com/113545468/229318923-496be669-5126-4d43-abc0-7c3e9b31357e.png)

* Case with parquet

![Screen Shot 2023-04-01 at 6 36 14 PM](https://user-images.githubusercontent.com/113545468/229319120-8f607e0a-1d68-4b3f-acba-7d8a1263a925.png)

## Conclusion

Based on the result, we can see that the performance of the queries in terms of the runtime has improved by 50% when caching and parquet were used. 




