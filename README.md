# Data-Cleaning-Preprocessing-Elevate-Lab-Task-1
This project involves cleaning and preprocessing the Netflix Movies and TV Shows dataset from Kaggle. It addresses real-world data issues like missing values, duplicates, inconsistent formats, and incorrect types. The result is a clean dataset ready for analysis, visualization, or machine learning tasks in data science workflows.

# Netflix Data Cleaning and Preprocessing

This notebook focuses on cleaning, preprocessing, and exploring the Netflix dataset to prepare it for machine learning tasks.

## 📌 Objective
- Clean raw Netflix data by handling missing values and outliers.
- Encode categorical features into numerical form.
- Explore feature correlations and identify redundant features.
- Scale numerical features for model readiness.

## 📂 Dataset
The dataset contains 8,807 entries and 12 columns, including:
- **show_id**: Unique ID for each show
- **type**: Movie or TV Show
- **title**: Title of the content
- **director**: Director name(s)
- **cast**: Cast members
- **country**: Country of origin
- **date_added**: Date added to Netflix
- **release_year**: Year the content was released
- **rating**: Age rating
- **duration**: Duration (minutes or seasons)
- **listed_in**: Genre(s)
- **description**: Summary description

## ⚙️ Key Steps
1. **Data Exploration**
   - Check dataset shape, data types, and null values.
   - Visualize missing data and basic statistics.

2. **Handling Missing Data**
   - Filled missing categorical values (e.g., director, country) with `"Unknown"`.
   - Verified no critical numeric data missing.

3. **Encoding**
   - Applied Label Encoding to `type`.
   - Planned One-Hot Encoding / additional encodings for other categorical features (as needed).

4. **Outlier Detection**
   - Used boxplots to visualize and remove outliers (where applicable).

5. **Feature Correlation**
   - Generated correlation matrix heatmaps.
   - No strong correlations found among features (no multicollinearity).

6. **Feature Scaling**
   - Applied standard scaling to `release_year` as an example.

## 📊 Results
- The dataset is cleaned and partially encoded.
- No redundant features detected via correlation.
- Ready for feature engineering and model building.

## 🚀 Next Steps
- Engineer new features (e.g., extract duration in numeric form, word count from description).
- Encode additional categorical features.
- Build machine learning models for classification or recommendation tasks.

## 🛠 Tools Used
- **Python 3**
- **Pandas**
- **NumPy**
- **Seaborn / Matplotlib**
- **Scikit-learn**

---

## 📎 How to Run
1. Open the notebook in Jupyter or any compatible environment.
2. Install required packages (if not already installed):
