# House Price Prediction

Machine Learning project developed as part of the **XYlofy AI Internship Program (Week 1)**.

---

# 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to analyze housing features, preprocess the dataset, train regression models, and evaluate their performance in predicting property prices.

The project follows a complete Machine Learning workflow including:

- Data Exploration
- Data Cleaning
- Feature Engineering
- Model Training
- Model Evaluation
- Data Visualization
- Feature Importance Analysis
- Business Insights

---

# 🎯 Objective

Build and compare Machine Learning models to predict house prices using housing characteristics such as:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Number of Stories
- Parking Availability
- Air Conditioning
- Furnishing Status
- Preferred Area
- Other Property Features

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

# 📂 Project Structure

```text
HousePricePrediction_AnushkaDas/
│
├── data/
│   ├── Housing.csv
│   └── Housing_Cleaned.csv
│
├── charts/
│   ├── house_price_distribution.png
│   ├── area_vs_price.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── feature_importance.png
│
├── reports/
│
├── House_Price_Prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🔍 Dataset Information

- **Dataset:** Housing Prices Dataset
- **Records:** 545
- **Features:** 13
- **Target Variable:** Price

The dataset contains information related to residential properties including location preferences, furnishing status, parking facilities, and other housing attributes.

---

# 📅 Project Progress

## Day 1 – Data Exploration

### Tasks Completed

- Created project structure
- Loaded dataset using Pandas
- Displayed first 10 rows
- Checked dataset dimensions
- Identified target and feature columns
- Performed missing value analysis
- Performed duplicate value analysis
- Identified categorical columns
- Conducted exploratory data analysis

### Key Findings

- Dataset contains 545 records and 13 features
- No missing values found
- No duplicate records found
- Multiple categorical features required encoding before model training

---

## Day 2 – Data Cleaning & Preprocessing

### Tasks Completed

- Created working copy of dataset
- Verified data quality
- Converted binary categorical features (**Yes/No → 1/0**)
- Applied One-Hot Encoding on furnishing status
- Created feature matrix (**X**)
- Created target variable (**y**)
- Generated cleaned dataset

### Key Findings

- Dataset required minimal cleaning
- No records needed removal
- All categorical features successfully converted into machine-learning-ready format

---

## Day 3 – Model Building & Evaluation

### Tasks Completed

- Performed Train-Test Split (**80/20**)
- Trained Linear Regression model
- Trained Random Forest Regressor
- Generated predictions
- Evaluated model performance
- Compared model results
- Analyzed feature importance

### Model Results

| Model | MAE | RMSE | R² Score |
|--------|---------:|---------:|---------:|
| Linear Regression | 970,043.40 | 1,324,506.96 | **0.6529** |
| Random Forest Regressor | 1,022,560.63 | 1,401,497.30 | 0.6114 |

### Best Performing Model

**Linear Regression**

The Linear Regression model achieved the highest R² score and the lowest prediction errors, making it the best-performing model for this dataset.

---

## Day 4 – Data Visualization & Feature Importance

### Tasks Completed

- Created House Price Distribution chart
- Created Area vs Price scatter plot
- Generated Correlation Heatmap
- Visualized Actual vs Predicted Prices
- Performed Feature Importance Analysis
- Identified major drivers of house prices

### Key Findings

- House prices show a right-skewed distribution.
- Property area has a positive relationship with house prices.
- Bathrooms, air conditioning, hot water heating, and preferred area emerged as major contributors to house prices.
- Linear Regression predictions closely follow actual prices.

---

## Day 5 – Final Analysis & Business Insights

### Tasks Completed

- Summarized project findings
- Generated business recommendations
- Documented limitations
- Proposed future improvements

---

# 📊 Key Insights

The most influential features affecting house prices were:

1. Bathrooms
2. Air Conditioning
3. Hot Water Heating
4. Preferred Area
5. Number of Stories

### Additional Observations

- Houses with more bathrooms generally command significantly higher prices.
- Air conditioning and hot water heating contribute positively to property value.
- Properties located in preferred areas tend to have higher market prices.
- Furnished homes are generally valued higher than unfurnished homes.
- Linear Regression outperformed Random Forest on this dataset.

---

# 📈 Visualizations

The project includes:

- House Price Distribution
- Correlation Heatmap
- Area vs Price Analysis
- Actual vs Predicted Price Comparison
- Feature Importance Analysis

---

# 💡 Business Recommendation

Real estate businesses should focus on promoting premium amenities such as:

- Additional Bathrooms
- Air Conditioning
- Hot Water Heating
- Preferred Locations
- Fully Furnished Properties

These features show a strong positive influence on house prices and can significantly improve property valuation.

---

# ⚠️ Limitations

- Dataset size is relatively small.
- Additional market variables were unavailable.
- Location information was limited.
- Economic indicators were not included.

These factors may impact prediction accuracy.

---

# 🚀 Future Improvements

- Collect larger datasets.
- Include geographical coordinates.
- Incorporate market trends.
- Experiment with XGBoost and LightGBM.
- Deploy the model as a web application.
- Use real-time housing data.

---

# ✅ Project Status

- ✅ Day 1 Completed
- ✅ Day 2 Completed
- ✅ Day 3 Completed
- ✅ Day 4 Completed
- ✅ Day 5 Completed
- ✅ Project Submitted

---

# 👩‍💻 Author

**Anushka Das**

**AI & Data Science Intern – XYlofy AI**

**GitHub:** AN-ai-del