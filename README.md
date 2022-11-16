# Pyspark-Assignment

. Amazon - Ecommerce
i.Extract:  Load the data
   - Read data as csv via spark dataframe

ii.Transform: Exploratory data analysis using spark df
    - Unique uniq_id count
    - format change in below columns
        price from £3.42 to 3.42
    - create column rating
       transform average_review_rating from 4.9 out of 5 stars to ->4.9
    - select columns uniq_id	product_name	manufacturer	price	number_available_in_stock	number_of_reviews	number_of_answered_questions	average_review_rating	amazon_category_and_sub_category ratings
    - format column amazon_category_and_sub_category (last element) from ---> Hobbies > Model Trains & Railway Sets > Rail Vehicles > Trains to Trains
    - show df
    - GroupBy amazon_category_and_sub_category and count

iii.Load: Save analysis report
    - show df, save as files 
    
    
    
