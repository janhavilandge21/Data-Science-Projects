#  Heart Disease Analysis
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Heart Disease dataset to uncover patterns and correlations between patient health attributes and heart disease risk.

Using Python, Pandas, Seaborn, and Matplotlib:

✅ Clean & preprocess the dataset

✅ Perform univariate, bivariate, and multivariate analysis

✅ Visualize patterns to understand risk factors for heart disease

✅ Derive key medical insights that could support early diagnosis

🏗️ Project Architecture

Raw Data → Data Cleaning → EDA → Visualization → Insights

Step 1: Load dataset & understand structure

Step 2: Clean & preprocess data

Step 3: Perform statistical analysis

Step 4: Visualize risk factors & correlations

Step 5: Summarize insights

📂 Dataset
Rows: 303 patients

Columns: 14 clinical features

Target: 1 (presence of heart disease) / 0 (no heart disease)

Column	Description
age	Patient age

sex	Gender (1 = Male, 0 = Female)

cp	Chest pain type

trestbps	Resting blood pressure (mm Hg)

chol	Serum cholesterol (mg/dl)

fbs	Fasting blood sugar > 120 mg/dl

restecg	Resting ECG results

thalach	Max heart rate achieved

exang	Exercise-induced angina

oldpeak	ST depression induced by exercise

slope	Slope of peak exercise ST segment

ca	Number of major vessels colored by fluoroscopy

thal	Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)

target	1 = heart disease, 0 = no heart disease


✅ No missing values

✅ Balanced target distribution (165 with disease, 138 without)

🛠️ Tech Stack
Language: Python 3

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Statistics: SciPy

🔍 Analysis Workflow
1️⃣ Data Cleaning
Checked dataset shape & column data types

Ensured no missing values

Validated numerical ranges

2️⃣ Univariate Analysis
Countplots for target distribution

Distribution of key features like age, chol, thalach

Boxplots for outlier detection

3️⃣ Bivariate Analysis
Relationship between sex & target

Effect of chest pain type (cp) on heart disease

Correlation of thalach (max heart rate) with disease presence

4️⃣ Multivariate Analysis
Correlation heatmap of all clinical features

Pairplots of important numerical features

📊 Sample Visualizations
✅ Countplots: Frequency of heart disease vs no disease
✅ Boxplots: Outlier detection for blood pressure, cholesterol
✅ Heatmap: Feature correlations with target variable
✅ Pairplot: Visual comparison of multiple risk factors

🚀 How to Run

2️⃣ Install Dependencies

pip install -r requirements.txt
3️⃣ Run Jupyter Notebook

jupyter notebook Heart_Disease_Analysis.ipynb
4️⃣ Explore Visualizations & Insights

💡 Key Insights

Chest pain type (cp) is highly correlated with heart disease risk

Higher max heart rate (thalach) is linked to fewer cases of disease

Oldpeak (ST depression) shows strong negative correlation with target

Males have a slightly higher proportion of heart disease compared to females

📌 Future Enhancements

Train Machine Learning models to predict heart disease risk

Build an interactive dashboard using Plotly or Streamlit

Deploy a Flask/Streamlit Web App for real-time predictions


