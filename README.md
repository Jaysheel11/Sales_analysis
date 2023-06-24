# Sales_analysis
Diwali sales analysis


Requirements:

Python

Pandas library

Numpy library

Matplotlib library

Seaborn library

Technologies Used:

Python: The programming language used for data analysis and visualization.

Pandas: A powerful data manipulation and analysis library used for handling datasets.

Numpy: A library for performing mathematical operations on arrays and matrices.

Matplotlib: A plotting library for creating visualizations.

Seaborn: A statistical data visualization library based on Matplotlib.


Steps Performed:
Import the necessary libraries: numpy, pandas, matplotlib.pyplot, and seaborn.

Read the CSV file containing the Diwali sales data into a pandas DataFrame using pd.read_csv.

Check the shape of the DataFrame to determine the number of rows and columns.

Display the first few rows of the DataFrame to get an initial glimpse of the data.

Obtain information about the DataFrame, including column names and data types.

Drop unrelated or blank columns from the DataFrame using df.drop.

Check for null values in the DataFrame using pd.isnull(df).sum().

Remove rows with null values from the DataFrame using df.dropna.

Convert the "Amount" column to the integer data type using df['Amount'] = df['Amount'].astype('int').

Display the column names of the DataFrame.

Rename the "Marital_Status" column to "Shaadi" using df.rename.

Calculate and display descriptive statistics of the DataFrame using df.describe().

Select specific columns ('Age', 'Orders', 'Amount') and display their descriptive statistics using df[['Age', 'Orders', 'Amount']].describe().

Perform exploratory data analysis on different aspects of the data, including gender, age, state, marital status, occupation, and product category.

Visualize the data using various plots such as bar plots, using functions from the matplotlib.pyplot and seaborn libraries.

Provide insights and conclusions based on the visualized data.
