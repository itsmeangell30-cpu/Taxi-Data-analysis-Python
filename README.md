# 🚕 Taxi Data Analysis Using Python
As a data analyst have to clean, analyze, and visualize taxi data. You will handle missing values, explore trends, and create visualizations to gain insights into fare, distance, and customer behavior using Pandas, Matplotlib, and Seaborn. 

📊 Data Cleaning | Exploratory Data Analysis | Data Visualization

📌 Project Overview
This project focuses on cleaning, analyzing, and visualizing taxi trip data using Python. The goal is to uncover meaningful insights into taxi trip patterns, fare distribution, trip distances, payment methods, tips, tolls, and pickup and drop-off locations.

Using Pandas, NumPy, Matplotlib, and Seaborn, this project demonstrates a complete data analysis workflow, from data preprocessing to exploratory data analysis (EDA) and visualization.

🎯 Project Objectives
🧹 Clean the dataset and handle missing values.
📅 Analyze taxi trip patterns over time.
💰 Explore fare, tip, toll, and total payment distributions.
🚖 Understand trip distance and passenger patterns.
💳 Identify the most commonly used payment methods.
📍 Analyze trips by pickup and drop-off boroughs and zones.
📈 Visualize relationships between numerical variables.
🔍 Generate meaningful insights from taxi trip data.
📂 Dataset Description
The dataset contains 14 columns describing taxi trips, including timestamps, passenger counts, distances, fares, payment methods, and geographic information.

Column	Description
pickup	Trip pickup date and time
dropoff	Trip drop-off date and time
passengers	Number of passengers
distance	Trip distance
fare	Base trip fare
tip	Tip amount
tolls	Toll charges
total	Total trip amount
color	Taxi color
payment	Payment method
pickup_zone	Pickup location zone
dropoff_zone	Drop-off location zone
pickup_borough	Pickup borough
dropoff_borough	Drop-off borough

🛠️ Tools and Technologies
🐍 Python – Programming language for data analysis.
🐼 Pandas – Data manipulation and cleaning.
🔢 NumPy – Numerical computations.
📊 Matplotlib – Data visualization.
🎨 Seaborn – Statistical visualization.
☁️ Google Colab – Interactive notebook environment.
🧹 Data Cleaning and Preprocessing
Before performing the analysis, the dataset was cleaned using the following steps:

🔎 Checked for missing values in all columns.
🧩 Identified columns containing null values.
🕒 Converted pickup and dropoff columns to datetime format.
🔢 Filled missing numerical values with the median where appropriate.
🏷️ Filled missing categorical values with the mode where appropriate.
✅ Rechecked the dataset after cleaning to verify missing-value handling.
These steps help improve data quality and prepare the dataset for reliable analysis.

📊 Data Visualization and Analysis
The project uses Matplotlib, Pandas plotting, and Seaborn to explore the taxi dataset through the following visualizations.

1. 📈 Line Chart — Average Fare Over Time
Examines how average taxi fares change over time.
Identifies daily trends and potential fluctuations in fares.
2. 💰 Bar Chart — Total Fare by Pickup Borough
Compares total fare revenue across pickup boroughs.
Identifies which borough contributes the highest total fare.
3. 💳 Pie Chart — Trips by Payment Method
Shows the proportion of trips associated with each payment method.
Identifies the most commonly used payment methods.
4. 📏 Histogram — Trip Distance Distribution
Visualizes the distribution of taxi trip distances.
Helps determine whether most trips are short or long.
5. 🎁 Box Plot — Tip Distribution by Pickup Borough
Compares tip amounts across pickup boroughs.
Highlights variation in tips and potential outliers.
6. 🚕 Count Plot — Number of Trips by Pickup Borough
Displays the number of trips originating in each borough.
Identifies the busiest pickup boroughs.
7. 🔗 Scatter Plot — Distance vs. Fare
Examines the relationship between trip distance and fare.
Helps determine whether fares generally increase with distance.
8. 🌡️ Heatmap — Correlation Between Numerical Variables
Displays correlations between numerical variables such as distance, fare, tip, tolls, and total.
Helps identify strong positive or negative relationships.
9. 🔍 Pair Plot — Relationships Between Numerical Variables
Explores pairwise relationships among distance, fare, tip, and total.
Helps identify patterns, trends, and potential outliers.
10. 🎻 Violin Plot — Fare Distribution by Payment Method
Compares fare distributions across payment methods.
Highlights differences in fare variability and distribution shape.
❓ Key Business Questions
This analysis helps answer the following questions:

📅 How do average taxi fares change over time?
💵 Which pickup borough generates the highest total fare?
💳 Which payment methods are used most frequently?
📏 What is the typical distribution of taxi trip distances?
🎁 How do tip amounts vary across pickup boroughs?
🚖 Which borough has the highest number of taxi pickups?
🔗 Is there a relationship between trip distance and fare?
🌡️ Which numerical variables have the strongest correlations?
📊 How do fare, distance, tips, and total amounts relate to each other?
🎻 How does fare distribution vary by payment method?
🔎 Analysis Areas
The project covers the following key areas:

🧹 Data cleaning and preprocessing
📅 Taxi trip trends over time
💰 Fare and total revenue analysis
📏 Trip distance analysis
💳 Payment method analysis
🎁 Tips and toll charges
📍 Pickup and drop-off boroughs and zones
🔗 Correlation and relationship analysis
📊 Statistical distributions and outlier detection
💡 Key Learnings
Through this project, I gained practical experience in:

Handling missing values and preparing datasets for analysis.
Working with datetime data in Pandas.
Performing exploratory data analysis (EDA).
Creating statistical and categorical visualizations.
Understanding relationships between numerical variables.
Identifying trends, distributions, and potential outliers.
Communicating data-driven findings through visualizations.
🚀 How to Run the Project
Option 1: Google Colab

Open the project notebook in Google Colab.
Upload the taxi dataset or connect to its storage location.
Install any required libraries if they are not already available.
Run the notebook cells sequentially.
Explore the resulting charts and analysis.
Option 2: Run Locally

Clone this repository:
   git clone <your-repository-url>
Navigate to the project folder:
   cd Taxi-Data-analysis-Python
Install the required libraries:
   pip install pandas numpy matplotlib seaborn jupyter
Launch Jupyter Notebook:
   jupyter notebook
Open the project notebook and run the cells.

Conclusion :
This project demonstrates an end-to-end data analysis workflow using Python, from cleaning missing data to exploring patterns and creating informative visualizations.

By analyzing taxi fares, distances, tips, payment methods, and pickup locations, the project develops practical skills in data preprocessing, exploratory data analysis, and statistical visualization.

🚀 Overall, this project showcases how Python libraries can transform raw taxi trip data into meaningful insights that support better understanding of taxi operations and customer behavior.

👨‍💻 Author
Angeline E

