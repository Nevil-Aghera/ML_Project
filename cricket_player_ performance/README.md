# 🏏 Cricket Player Performance Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 📌 Project Overview

This project analyzes cricket player performance data and uses machine learning classification algorithms to predict the **Match Result**.

The notebook performs data cleaning, exploratory data analysis (EDA), feature engineering, categorical encoding, feature scaling, train-test splitting, model training, model comparison, prediction, and visualization.

## 📊 Dataset

The project uses a CSV dataset containing **40,000 records and 16 columns**.

### Dataset Columns

| # | Column | Description |
|---|---|---|
| 1 | 📅 Date | Match date |
| 2 | 👤 Player_Name | Cricket player name |
| 3 | 🏏 Team | Player's team |
| 4 | 🆚 Opponent | Opponent team |
| 5 | 🏃 Runs | Runs scored |
| 6 | 🎯 Balls_Faced | Balls faced by the player |
| 7 | 4️⃣ Fours | Number of fours |
| 8 | 6️⃣ Sixes | Number of sixes |
| 9 | 🎳 Wickets | Wickets taken |
| 10 | 📉 Economy_Rate | Bowling economy rate |
| 11 | 🏆 Match_Result | Match result / target variable |
| 12 | 🏟️ Match_Type | Type of match |
| 13 | ⭐ Player_Impact_Score | Player impact score |
| 14 | ⚡ Strike_Rate | Batting strike rate |
| 15 | 🧤 Catches | Catches taken |
| 16 | 🎯 Target_Score | Target score |

## 🧰 Technologies & Libraries

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🎨 Seaborn
- 🤖 Scikit-learn
- 📓 Jupyter Notebook / Google Colab

## 🔄 Project Workflow

```text
📥 Import Data
      ↓
🧹 Data Cleaning
      ↓
🔎 Exploratory Data Analysis (EDA)
      ↓
🛠️ Feature Engineering
      ↓
🏷️ Label Encoding
      ↓
📏 Min-Max Feature Scaling
      ↓
✂️ Train-Test Split
      ↓
🤖 Train ML Models
      ↓
📈 Evaluate Models
      ↓
🏅 Compare Model Accuracy
      ↓
🔮 Prediction
      ↓
📊 Visualizations
```

## 🧹 Data Preprocessing

The notebook includes:

- Replacement of `?` placeholders with missing values.
- Missing-value checking.
- Duplicate-row checking and removal.
- Mean imputation for numerical columns when required.
- Most-frequent imputation for categorical columns when required.
- Date conversion and extraction of:
  - `Match_Year`
  - `Match_Month`
- Removal of the original `Date` column after feature extraction.
- Label encoding of categorical columns.
- Min-Max scaling of numerical features.

## 🔍 Exploratory Data Analysis

The notebook includes:

- 📊 Match result distribution
- 🏟️ Match type distribution
- 🔥 Numeric feature correlation heatmap

## 🤖 Machine Learning Models

The following classification algorithms are trained and evaluated:

1. 🔵 **SVM — Support Vector Machine**
2. 🧠 **Naive Bayes**
3. 👥 **K-Nearest Neighbors (KNN)**
4. 🌳 **Decision Tree**
5. 🌲 **Random Forest**

### 🎯 Target Variable

```text
Match_Result
```

The dataset is split into:

- **70% Training Data**
- **30% Testing Data**

## 📏 Model Evaluation

Each model is evaluated using:

- 🎯 Accuracy
- 🧮 Confusion Matrix
- 📋 Classification Report

The notebook creates a model comparison table and sorts models by accuracy to identify the best-performing model.

## 🔮 Prediction

The best-performing model is selected automatically based on the highest test accuracy.

The notebook then compares:

- ✅ Actual Match Result
- 🔮 Predicted Match Result

for the first 10 test samples.

## 📈 Visualizations

The notebook contains:

- 📊 Match Result Count Plot
- 🏟️ Match Type Count Plot
- 🔥 Correlation Heatmap
- ⚡ Runs vs Strike Rate Scatter Plot
- 📉 Histograms of important numerical attributes
- 📦 Box Plot of encoded Match Result
- 📦 Box Plots for key numerical statistics
- 🧮 Confusion Matrix Heatmaps for all models
- 🏅 Model Accuracy Comparison Bar Chart

## 📁 Project Files

```text
📦 Cricket Player Performance
│
├── 📓 cricket_player_ performance(1).ipynb
├── 📄 cricket_player_ performance(1).csv
├── 📘 README.md
└── 📝 README.txt
```

## ▶️ How to Run

### 💻 Jupyter Notebook

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open Jupyter Notebook.
4. Open `cricket_player_ performance(1).ipynb`.
5. Make sure the CSV dataset is available at the path expected by the notebook.
6. Run the cells from top to bottom.

### ☁️ Google Colab

1. Open Google Colab.
2. Upload the `.ipynb` notebook.
3. Upload the CSV dataset.
4. Update the CSV path if required.
5. Run all cells.

## 👨‍💻 Project Information

**Project:** Cricket Player Performance Analysis & Prediction  
**Dataset Size:** 40,000 records  
**Number of Features/Columns:** 16  
**Task:** Classification  
**Target:** `Match_Result`

## ⭐ Key Highlights

- 🏏 Cricket performance data analysis
- 🧹 Complete preprocessing workflow
- 🔎 EDA and visualization
- 🤖 Multiple machine learning algorithms
- 📊 Model comparison
- 🔮 Automatic best-model selection
- 🧮 Confusion matrix analysis
- 📈 Performance visualization

---

### 🏆 Cricket Player Performance — Analyze • Predict • Visualize
