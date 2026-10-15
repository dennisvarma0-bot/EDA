Theory: Exploratory Data Analysis (EDA)
Aim
To perform Exploratory Data Analysis (EDA) on the Iris dataset using Python libraries such as Pandas, Matplotlib, and Seaborn to understand the dataset, identify missing values and duplicate records, calculate statistical summaries, and visualize the relationships between different features.

Introduction
Exploratory Data Analysis (EDA) is the process of analyzing and summarizing a dataset to understand its main characteristics. It helps identify patterns, trends, relationships, missing values, and duplicate records before applying statistical methods or machine learning algorithms.

Python provides several libraries for performing EDA. Pandas is used for data manipulation and analysis, Matplotlib is used for creating graphs, and Seaborn is used for statistical data visualization.

Dataset Description
The Iris dataset is a commonly used dataset in data analysis and machine learning. It contains 150 observations of iris flowers belonging to three species: Setosa, Versicolor, and Virginica.

The dataset contains five columns:

Sepal Length: Length of the flower's sepal.

Sepal Width: Width of the flower's sepal.

Petal Length: Length of the flower's petal.

Petal Width: Width of the flower's petal.

Species: The category or species of the iris flower.

Methodology
1. Loading the Dataset: The Iris dataset is loaded using the Seaborn library and stored in a Pandas DataFrame for analysis.

2. Displaying the First Five Rows: The head() function displays the first five records to understand the structure and contents of the dataset.

3. Dataset Information: The info() function provides information about column names, data types, and the number of non-null values.

4. Statistical Summary: The describe() function calculates statistical measures such as mean, standard deviation, minimum, maximum, and quartiles for numerical columns.

5. Checking Missing Values: The isnull().sum() function identifies the number of missing values in each column.

6. Checking Duplicate Rows: The duplicated().sum() function counts duplicate records in the dataset.

7. Displaying Column Names: The columns attribute displays the names of all columns in the dataset.

8. Histogram Visualization: Histograms are used to understand the distribution and frequency of values for each numerical feature.

9. Correlation Heatmap: A correlation heatmap represents the relationships between numerical variables. Positive correlation indicates that two variables tend to increase together, while negative correlation indicates that one tends to decrease as the other increases.

10. Scatter Plot: A scatter plot is used to examine the relationship between sepal length and petal length for the three flower species.

11. Box Plot: A box plot compares the distribution of petal length across different species and helps identify variation, median values, and potential outliers.

Result
Exploratory Data Analysis was performed successfully on the Iris dataset. The analysis provided information about the dataset's structure, statistical properties, missing values, duplicate records, feature distributions, and relationships between numerical variables. The visualizations also helped identify differences among the three iris species.
