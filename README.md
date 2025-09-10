# Water Potability Prediction

This project aims to predict the potability of water based on various parameters. The analysis and model building are performed using Python with libraries like pandas, numpy, seaborn, plotly, matplotlib, and scikit-learn.

## Dataset

The dataset used in this project is `water_potability.csv`, which contains different water quality parameters and a target variable indicating whether the water is potable or not.

## Project Structure

The notebook covers the following steps:

1.  **Loading Libraries**: Importing necessary libraries for data manipulation, visualization, and machine learning.
2.  **Loading Data**: Reading the `water_potability.csv` file into a pandas DataFrame.
3.  **Exploratory Data Analysis (EDA)**:
    *   Checking the column names and data types.
    *   Generating descriptive statistics of the dataset.
    *   Checking for missing values using `isnull().sum()` and visualizing them with a heatmap.
    *   Visualizing the correlation matrix between features.
    *   Analyzing the distribution of the target variable 'Potability'.
    *   Creating box plots to visualize the distribution of each feature.
    *   Generating pair plots to visualize relationships between features.
    *   Using plotly to create interactive visualizations (pie chart for potability distribution, scatter plots for 'ph' vs 'Sulfate' and 'Organic_carbon' vs 'Hardness' colored by potability).
    *   Visualizing the percentage of missing values per feature using a bar plot.
4.  **Data Preprocessing**:
    *   Handling missing values by filling them with the mean of the respective columns ('ph', 'Sulfate', 'Trihalomethanes').
    *   Verifying that missing values have been handled by checking `isnull().sum()` and a heatmap.
    *   Separating features (X) and the target variable (y).
    *   Scaling the features using `StandardScaler`.
    *   Splitting the data into training and testing sets.

## How to Run the Notebook

1.  Clone the repository.
2.  Install the required libraries:
