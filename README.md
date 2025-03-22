# Titanic-Data-Analysis
This project analyzes the Titanic dataset to predict passenger survival using various machine learning techniques.

1. Data Exploration and Preprocessing:<br>
The project begins by loading the Titanic dataset and exploring its structure, including data types and missing values.<br>

2. Data cleaning is performed to handle missing values:<br>

The "Cabin" column, with a high number of missing values, is removed.<br>

Missing values in the "Embarked" column are filled using the most frequent value (mode).<br>

Missing values in the "Age" column are imputed using linear interpolation.<br>

3. Outliers in the "Age" column are handled using the Interquartile Range (IQR) method to ensure data quality.<br>

4. Data scaling and normalization techniques are applied:<br>

Standardization (using StandardScaler) to center data around zero with unit variance.<br>

Normalization (using MinMaxScaler) to scale data to a specific range (0 to 1).<br>

Z-score normalization to transform data based on standard deviations from the mean.<br>

Feel free to download the code and data.
