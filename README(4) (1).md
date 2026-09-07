# ✈️ Flight Price Analysis & Data Visualization

## 📌 Project Overview

This project focuses on data cleaning, exploratory data analysis (EDA), and visualization of flight price data. The objective is to analyze factors affecting flight prices and extract meaningful insights using Python data analysis techniques.

## 🎯 Objectives
- Perform data understanding and data cleaning
- Handle missing values and duplicate records
- Detect and handle outliers
- Analyze flight price patterns
- Visualize relationships between features
- Generate insights from the dataset

## 📂 Dataset Information
The dataset contains 300,153 flight records with 11 features.

| Feature | Description |
|---|---|
| airline | Name of airline |
| flight | Flight number |
| source_city | Departure city |
| destination_city | Arrival city |
| departure_time | Departure time category |
| arrival_time | Arrival time category |
| stops | Number of stops |
| class | Ticket class |
| duration | Flight duration |
| days_left | Days remaining before departure |
| price | Flight ticket price |

## 🛠️ Technologies Used
- Python
- Jupyter Notebook

Libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Project Workflow

### 1. Data Understanding
- Dataset shape analysis
- Data type checking
- Statistical summary

### 2. Data Cleaning
- Checked missing values
- Removed unnecessary columns
- Handled duplicate records
- Corrected dataset structure

### 3. Outlier Detection & Handling
Outliers were detected using boxplot visualization and handled using the IQR method with capping.

## 📊 Visualizations
- Flight Price Distribution
- Average Flight Price by Airline
- Class vs Price Analysis
- Airline Flight Count
- Duration vs Price Relationship
- Correlation Heatmap

## 📈 Key Insights
- Flight prices vary depending on airline and ticket class.
- Business class tickets are generally more expensive.
- Duration and days left influence pricing patterns.
- Airlines show different average pricing trends.

## 📁 Project Structure
```
Flight-Price-Analysis/
│
├── Clean_Dataset.csv
├── Flight_Price_Analysis.ipynb
├── README.md
└── Visualizations/
```

## 🚀 How to Run
Install libraries:
```
pip install pandas numpy matplotlib seaborn
```

Run:
```
jupyter notebook
```

Open the notebook file.

## ✅ Conclusion
This project demonstrates the complete data analysis workflow including data cleaning, outlier handling, exploratory analysis, and visualization to understand flight price patterns.

## 👩‍💻 Author
Aditi Gawade  
BE Artificial Intelligence & Data Science
