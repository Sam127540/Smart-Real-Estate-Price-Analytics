# Smart Real Estate Price Analysis 🏡

## Project Overview
This project analyzes residential property prices using Python and data analysis libraries. It explores house prices, living area, bedrooms, property age, renovation status, and location-based price differences.

## Objectives
- Clean and preprocess the housing dataset.
- Perform Exploratory Data Analysis (EDA).
- Analyze the relationship between living area and house prices.
- Compare average house prices across bedrooms and zipcodes.
- Create new features for deeper analysis.
- Categorize properties into budget, mid-range, and luxury segments.
- Present findings through visualizations.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset
The dataset contains 21,613 housing records with information such as price, bedrooms, bathrooms, living area, lot size, condition, grade, year built, renovation year, and zipcode.

## Data Cleaning and Preprocessing
- Removed the unnecessary `Unnamed: 0` column.
- Checked for and removed duplicate rows.
- Filled missing bedroom and bathroom values using their respective medians.
- Converted the date column to datetime format.
- Checked for remaining missing values.

## Feature Engineering
The following features were created:
- `house_age`: Estimated property age using 2015 as the reference year.
- `is_renovated`: Indicates whether a renovation year is recorded.
- `price_per_sqft`: House price divided by living area.
- `price_category`: Groups properties into Budget, Mid-Range, and Luxury categories.

## Exploratory Data Analysis and Visualizations
- House price distribution.
- Living area versus house price.
- Average house price by number of bedrooms.
- Top 10 zipcodes by average house price.
- Correlation heatmap of numerical features.
- Property counts by price category.

## Key Findings
- Total housing records: 21,613.
- Average house price: approximately $540,088.
- Median house price: $450,000.
- Minimum house price: $75,000.
- Maximum house price: $7,700,000.
- Correlation between living area and price: approximately 0.702.
- Zipcode 98039 has the highest average house price in this dataset.

## Conclusion
The analysis explores the association between property size, location, and house prices. Feature engineering and price categorization provide additional ways to compare properties. These findings describe patterns in the available dataset and do not guarantee future property prices.

## How to Run the Project
1. Download the notebook and CSV dataset.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the CSV dataset if needed.
4. Update the dataset path in the code if necessary.
5. Run the notebook cells in order.

## Author
Data Analysis Project
