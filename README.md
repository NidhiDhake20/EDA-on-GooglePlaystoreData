# EDA-on-GooglePlaystoreData
This project focuses on performing Exploratory Data Analysis (EDA) and Feature Engineering on the Google Play Store dataset, which contains over 10,000 apps and 20 attributes.
The goal is to uncover insights about app performance, popularity trends, and key factors that influence installs and ratings and user engagement while improving data quality through cleaning and transformation.

🎯 Objectives
Identify the most popular app categories
Find apps with the highest installs and ratings
Analyze relationships between size, price, category, and reviews
Handle missing values, duplicates, and inconsistent entries
Create visualizations to communicate insights effectively

🧩 Dataset
Source: Google Play Store Dataset (googleplaystore.csv)
Shape: 10,841 rows × 20 columns

Key Features:
App – Name of the application
Category – Type of app (e.g., GAME, TOOLS, EDUCATION)
Rating – Average user rating
Reviews – Number of user reviews
Size – App size (in MB)
Installs – Total downloads
Type – Free or Paid
Price – Price (if paid)
Content Rating – Age group suitability

⚙️ Tools & Libraries
Python 3
Pandas – Data cleaning & manipulation
NumPy – Numerical computations
Matplotlib – Data visualization
Seaborn – Advanced statistical plotting

🧠 Process
Data Cleaning – Handled missing values, formatted columns, and removed duplicates
Feature Engineering – Processed categorical and numeric data for deeper insights
Exploratory Data Analysis (EDA) – Used visualizations to uncover trends and relationships
Insights Extraction – Highlighted patterns in app ratings, installs, and categories

📊 Key Insights
The Game and Tools categories dominate in total installs.
Larger app sizes don’t always guarantee better ratings.
Free apps tend to have more downloads, but ratings vary widely.
Duplicate and missing records required extensive preprocessing.

📈 Visual Highlights
Distribution of app ratings
Correlation between reviews and installs
Most downloaded categories
Relationship between app size and rating

💡 Learnings
Enhanced understanding of data preprocessing and cleaning
Improved ability to visualize and interpret real-world datasets
Strengthened EDA workflow skills using Python
