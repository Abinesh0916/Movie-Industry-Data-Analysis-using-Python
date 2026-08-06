# Movie-Industry-Data-Analysis-using-Python
This project analyzes a movie dataset using Pandas, Matplotlib, and Seaborn. It covers data cleaning, exploratory data analysis, and visualization to identify patterns, trends, and relationships among budget, gross revenue, ratings, genres, directors, writers, and stars.
# 🎬 Movie Industry Exploratory Data Analysis (EDA)

## 📌 Overview

This project performs Exploratory Data Analysis (EDA) on a movie industry dataset using Python. The objective is to clean the dataset, analyze movie-related features, and visualize patterns that influence a movie's commercial and critical success.

## 🚀 Features

* Data loading and inspection
* Data type conversion and preprocessing
* Missing value analysis
* Release date formatting
* Country extraction from release information
* Categorical data mapping (movie ratings)
* Data visualization using Matplotlib and Seaborn
* Relationship and trend analysis

## 📊 Visualizations Included

* Genre distribution (Count Plot)
* Gross Revenue by Genre (Bar Plot)
* IMDb Score by Genre (Bar Plot)
* Budget vs Gross Revenue (Regression Plot)
* Pair Plot for Budget, Gross, Votes, and Score
* Top 10 Directors by Number of Movies
* Top 10 Writers by Number of Movies

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## 📂 Dataset

The project uses the **Movies Dataset**, which contains information such as:

* Movie Name
* Genre
* Release Date
* Country
* Budget
* Gross Revenue
* IMDb Score
* Votes
* Director
* Writer
* Star
* Runtime
* Rating

## 📈 Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Explore the dataset using `head()`, `info()`, and `dtypes`.
4. Identify and handle missing values.
5. Clean and transform data:

   * Convert numerical columns to appropriate data types.
   * Extract release country from the `released` column.
   * Convert release dates into a standard datetime format.
   * Map movie ratings to descriptive labels.
6. Perform Exploratory Data Analysis (EDA).
7. Create visualizations to discover trends and relationships.
8. Draw insights from the analyzed data.

## 🔍 Key Insights

* Movie budget has a positive relationship with gross revenue.
* Some genres consistently generate higher revenue than others.
* Highly rated movies often receive more audience votes.
* A small number of directors and writers contribute to a large portion of the movies in the dataset.
* Data visualization helps identify trends, outliers, and correlations among movie attributes.

## ▶️ How to Run

1. Clone this repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Place the `movies.csv` dataset in the project directory.
4. Run the notebook cells sequentially.

## 📄 License

This project is intended for educational and learning purposes.

