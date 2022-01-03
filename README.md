# Performing Exploratory Data Analysis (EDA) on a sales dataset using Pandas, Numpy and Matplotlib

Exploratory data analysis steps that have been followed:

1. Perform data preparation and cleaning using Pandas and Numpy (ex:handle missing data)
2. Perform exploratory data analysis and visualisations using Matplotlib and Seaborn.
3. Ask and answer questions about the data and answer them by analysing the data and visualisations of relevant features
4. Summarise your inferences and write a conclusion

## Detailed description of the procedures I have followed

I have been analyzing and answering business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I started by cleaning the data. Tasks during this section include:

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once I have cleaned up the data a bit, I move the data exploration section. In this section I explore 5 high level business questions related to the data:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I walk through many different pandas & matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize the results
- Labeling the graphs

## Author and Purpose

- Artem Moshnin, 2022
- Made for examination of Tinkoff Bank Machine Learning Course
