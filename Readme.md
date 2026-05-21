# Brief Summary

# Objective

The main goal of this project was to learn about Python and use the Pandas library to explore and clean an ecommerce dataset called "Combined_dataset.csv".

# Tasks Performed

1. Loading the Dataset:-

I loaded the "Combined_dataset.csv" dataset into a Pandas DataFrame using the read_csv function. This was the step in my project.

2. Exploring the Dataset:-

To understand the dataset I used functions.

- I used head to see the first 5 rows.
- I used tail to see the last 5 rows.
- I checked the shape to see how many rows and columns the dataset had.
- I looked at the columns to see all the column names.
- I checked the data types to see what kind of data was in each column.
- I used info to get all the information about the dataset.

3. Handling Missing Values:-

I found missing values using isnull. Then I filled in the missing values in the columns with the average value. For the text columns I filled in the missing values with a custom value that made sense.

4. Performing Basic Operations:-

I did some things with the data.
- I picked the columns that were important.
- I filtered out rows based on the price of the product.
- I showed some information about the products.

5. Removing Duplicate Data:-

I. Removed duplicate rows in the dataset using drop_duplicates. This helped make the data better.

6. Creating a Derived Column:-

I made a column called total_amount. To do this I multiplied the price by the Quantity.
Since the dataset did not have a Quantity column I made a custom one for this calculation.

7. Saving the Cleaned Dataset:-
After I finished cleaning and transforming the data I saved the cleaned dataset as a file called cleaned_dataset.csv.

# Technologies Used

- I used Python for this project.
- I used Pandas to work with the data.
- I used Jupyter Notebook to write and run my code.

# Conclusion
"This project taught me a lot, about data analysis and cleaning using Pandas. I learned how to work with datasets handle missing values find information make new columns and save cleaned data into a new CSV file. The ecommerce dataset "Combined_dataset.csv" was an example to practice on. I gained a lot of experience working with the Pandas library on this ecommerce dataset "Combined_dataset.csv"."