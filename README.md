
# Used Cars Data Analysis

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of a used car dataset using Python. The main objective is to understand the dataset, identify missing values and potential outliers, and visualize patterns and relationships among different car features, especially used car prices.

## Objectives
- Understand the structure and characteristics of the dataset.
- Identify missing values and duplicate records.
- Perform descriptive statistical analysis.
- Analyze used car prices and new car prices.
- Explore fuel type distribution and mileage patterns.
- Identify potential outliers in car prices.
- Visualize relationships between numerical variables using a correlation heatmap.

## Dataset Description
The dataset contains 7,253 records and 14 columns.

Important columns include:
- **Name:** Name and model of the car.
- **Location:** City where the car is listed.
- **Year:** Manufacturing year of the car.
- **Kilometers_Driven:** Distance driven by the car.
- **Fuel_Type:** Fuel used by the car.
- **Transmission:** Manual or automatic transmission.
- **Owner_Type:** Ownership category.
- **Mileage:** Fuel efficiency of the car.
- **Engine:** Engine capacity.
- **Power:** Engine power.
- **Seats:** Number of seats.
- **New_Price:** New car price.
- **Price:** Used car price.

## Technologies and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Analysis Performed

### 1. Data Loading and Inspection
Loaded the dataset using Pandas and examined its shape, first and last records, column names, data types, and statistical summary.

### 2. Duplicate Records
Checked for duplicate rows. The dataset contains no duplicate records according to the duplicate check performed.

### 3. Missing Value Analysis
Identified missing values in several columns:
- Price: 1,234
- New_Price: 6,247
- Mileage: 2
- Engine: 46
- Power: 46
- Seats: 53

Missing values were examined to understand the data quality issues.

### 4. Price Analysis
Examined the `Price` and `New_Price` columns and checked their data types. The used car price is numeric, while the new car price contains text and units such as "Lakh".

### 5. Fuel Type Analysis
Analyzed the distribution of cars across different fuel types using value counts and a count plot.

### 6. Data Visualization
Created visualizations to explore the dataset:
- Histograms to examine price and mileage distributions.
- A scatter plot to explore the relationship between mileage and price.
- A box plot to investigate potential price outliers across transmission types.
- A bar chart to compare average used car prices by manufacturing year.
- A count plot to compare fuel types.
- A correlation heatmap to examine relationships among numerical variables.

## Key Findings
- The dataset contains 7,253 records and 14 columns.
- No duplicate rows were detected.
- Diesel is the most common fuel type, with 3,852 records.
- Petrol is the second most common fuel type, with 3,325 records.
- The `Price` column contains 1,234 missing values.
- The `New_Price` column contains 6,247 missing values, making it the column with the most missing data.
- Price distribution and box plots can help identify unusually priced cars for further investigation.

## Project Workflow
1. Import the required Python libraries.
2. Load the used car dataset.
3. Inspect the data and its structure.
4. Check for duplicates and missing values.
5. Perform descriptive statistical analysis.
6. Analyze important columns.
7. Create visualizations.
8. Interpret the results and summarize the findings.

## How to Run the Project
1. Open Google Colab or Jupyter Notebook.
2. Upload the `used_cars_data.csv` dataset.
3. Import Pandas, NumPy, Matplotlib, and Seaborn.
4. Update the dataset file path if necessary.
5. Run the notebook cells in sequence.
6. Review the outputs, charts, and analysis.

## Conclusion
This project demonstrates how Python can be used to perform exploratory data analysis on used car data. It helps identify data quality issues, understand the distribution of car prices and fuel types, investigate potential outliers, and visualize relationships between numerical features.

The analysis provides a foundation for further data cleaning and more advanced analysis, such as used car price prediction, if required.

## Future Improvements
- Handle missing values using appropriate methods.
- Convert columns containing units into suitable numerical formats.
- Investigate and validate potential outliers.
- Perform additional feature analysis.
- Build a machine learning model to predict used car prices, if required.
