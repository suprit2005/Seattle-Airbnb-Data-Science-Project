This project analyzes the Seattle Airbnb dataset using a complete Data Science workflow—from SQL-based data cleaning to Python Exploratory Data Analysis (EDA), Power BI visualization, and basic Machine Learning modeling.
The objective is to uncover meaningful insights about Airbnb listings, pricing patterns, neighborhood trends, and host behavior.

The final outcome includes:
✔ Clean SQL-processed dataset
✔ In-depth Python EDA
✔ Interactive Power BI Dashboard
✔ Basic ML model for price prediction

Project Objectives
Understand key factors that influence Airbnb listing prices in Seattle

Analyze location-based trends (neighborhood, room type, availability)

Build an interactive dashboard to explore pricing, reviews, and demand

Perform basic ML modeling to predict listing price based on key features

Dataset
The dataset includes key features such as:

Listing ID, Host ID

Name & Description

Neighbourhood

Room Type

Price

Minimum Nights

Number of Reviews

Availability 365

Review Scores

Amenities

Tech Stack & Tools
SQL
Data cleaning

Removing duplicates & nulls

Standardizing categorical values

Basic quality checks

Python (Jupyter Notebook)
Pandas – Data manipulation

NumPy – Numerical processing

Matplotlib & Seaborn – EDA & visualizations

Scikit-learn – Basic ML (price prediction)

Power BI
Dashboard creation

DAX for calculated measures

Interactive filters & slicers

KPI cards and visual insights

 Steps Performed
 1. Data Cleaning – SQL
Handled missing values and inconsistent entries

Normalized neighborhood, room type, and review attributes

Removed duplicate rows

Converted data types for analysis

Exported clean dataset for Python processing

 2. Exploratory Data Analysis – Python
Key analyses include:

Price distribution & outliers

Room type comparison

Neighborhood-wise price patterns

Correlation analysis

Availability trends

Review score relationships

 3. Power BI Dashboard
The dashboard highlights:

Average price by neighborhood

Room type distribution

Review trends

Host activity

Availability and seasonal demand

Filters for neighborhood, room type, and price range

 4. Machine Learning Model
Feature engineering

Train–test split

Linear Regression / Random Forest (basic version)

Evaluated using RMSE / R²

Insights on the most impactful features

 Key Insights
Certain Seattle neighborhoods have significantly higher pricing due to location demand

Private rooms and entire homes show clear pricing and review differences

Review scores correlate strongly with pricing for premium listings

Availability varies seasonally, affecting price and occupancy

Simple ML models can reasonably estimate listing prices using key features

 Outcome
This project demonstrates a complete mini-pipeline for data science work:
✔ SQL cleaning → ✔ Python EDA → ✔ Power BI Dashboard → ✔ ML Modeling

It provides actionable insights into Seattle Airbnb pricing and helps understand how data can be transformed into interactive business intelligence.
