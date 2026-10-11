# 🚕 Taxi Data Analysis Using Python
As a data analyst have to clean, analyze, and visualize taxi data. You will handle missing values, explore trends, and create visualizations to gain insights into fare, distance, and customer behavior using Pandas, Matplotlib, and Seaborn. 


📊 Data Cleaning | Exploratory Data Analysis | Data Visualization

📌 Project Overview
This project analyzes taxi trip data using Python. The goal is to discover patterns in fares, distances, tips, and customer behavior. The project uses Pandas, NumPy, Matplotlib, and Seaborn.

🎯 Project Objectives
🧹 Clean data and handle missing values.
📅 Analyze taxi trip trends over time.
💰 Explore fares, tips, tolls, and total amounts.
🚖 Analyze trip distances and passenger counts.
💳 Understand payment method preferences.
📍 Explore pickup and drop-off locations.
📈 Create meaningful data visualizations.

📂 Dataset Description
The dataset contains 14 columns related to taxi trips.

🕒 pickup – Pickup date and time.
🕒 dropoff – Drop-off date and time.
👥 passengers – Number of passengers.
📏 distance – Trip distance.
💵 fare – Base trip fare.
🎁 tip – Tip amount.
🛣️ tolls – Toll charges.
💰 total – Total trip amount.
🚕 color – Taxi color.
💳 payment – Payment method.
📍 pickup_zone – Pickup location zone.
📍 dropoff_zone – Drop-off location zone.
🏙️ pickup_borough – Pickup borough.
🏙️ dropoff_borough – Drop-off borough.


🛠️ Tools and Technologies
🐍 Python
🐼 Pandas
🔢 NumPy
📊 Matplotlib
🎨 Seaborn
☁️ Google Colab


🧹 Data Cleaning
🔍 Checked missing values in the dataset.
🧩 Identified columns containing null values.
🕒 Converted pickup and drop-off columns to datetime.
🔢 Filled missing numerical values with the median when appropriate.
🏷️ Filled missing categorical values with the mode when appropriate.
✅ Rechecked the dataset after cleaning.


📊 Data Visualization
1. 📈 Line Chart
Analyzes average taxi fares over time.
Identifies changes in fares across different days.
2. 💰 Bar Chart
Displays total fare by pickup borough.
Identifies boroughs generating the highest total fares.
3. 💳 Pie Chart
Shows the distribution of trips by payment method.
Identifies the most commonly used payment methods.
4. 📏 Histogram
Displays the distribution of taxi trip distances.
Helps identify short and long trips.
5. 🎁 Box Plot
Compares tip amounts across pickup boroughs.
Highlights variation and potential outliers.
6. 🚖 Count Plot
Shows the number of trips by pickup borough.
Identifies the busiest pickup locations.
7. 🔗 Scatter Plot
Explores the relationship between distance and fare.
Checks whether fares increase with trip distance.
8. 🌡️ Heatmap
Displays correlations between numerical variables.
Examines distance, fare, tips, tolls, and total amounts.
9. 🔍 Pair Plot
Explores relationships between distance, fare, tip, and total.
Helps identify patterns and potential outliers.
10. 🎻 Violin Plot
Compares fare distributions across payment methods.
Shows differences in fare variation.


❓ Key Questions
📅 How do average fares change over time?
💰 Which pickup borough generates the highest total fare?
💳 Which payment method is most popular?
📏 Are most taxi trips short or long?
🎁 How do tips vary across boroughs?
🚕 Which borough has the most pickups?
🔗 Is distance related to fare?
🌡️ Which numerical variables have strong correlations?
🎻 How do fares vary by payment method?


🔎 Analysis Areas
🧹 Data cleaning and preprocessing.
📅 Trip trends and time-based analysis.
💵 Fare and revenue analysis.
📏 Trip distance analysis.
💳 Payment method analysis.
🎁 Tips and tolls analysis.
📍 Borough and zone analysis.
📊 Correlation and distribution analysis.

💡 Key Learnings
Learned to handle missing data using Pandas.
Practiced datetime conversion and data preprocessing.
Performed exploratory data analysis (EDA).
Created visualizations using Matplotlib and Seaborn.
Explored correlations and relationships between variables.
Identified patterns, distributions, and potential outliers.

🚀 How to Run the Project
Download or clone this repository.
Open the notebook in Google Colab or Jupyter Notebook.
Upload the taxi dataset.
Install the required Python libraries.
Run the notebook cells sequentially.
Review the visualizations and analysis results.

📦 Installation
Run the following command to install the required libraries:

pip install pandas numpy matplotlib seaborn jupyter
📁 Project Structure
Taxi-Data-analysis-Python/
├── data/
│   └── taxi_data.csv
├── Taxi_Data_Analysis.ipynb
├── README.md
└── requirements.txt
🏁 Conclusion
This project demonstrates the complete data analysis workflow. It covers data cleaning, exploratory analysis, and visualization. The analysis explores taxi fares, distances, tips, payments, and locations. It provides practical experience with Python data analysis libraries. The visualizations help communicate patterns and relationships in taxi data.

👨‍💻 Author
Name: Angeline E

