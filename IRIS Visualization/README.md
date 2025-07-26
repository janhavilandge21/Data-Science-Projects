# 🌸 Iris Dataset Visualization
📌 Project Overview
This project visualizes the famous Iris dataset using Seaborn & Matplotlib to explore patterns and relationships between different flower species.

It includes:
✅ Univariate, Bivariate, and Multivariate visualizations

✅ Distribution analysis of Sepal & Petal measurements

✅ Comparison of 3 species: Iris-setosa, Iris-versicolor, Iris-virginica

✅ Different plot types (Boxplot, Violin, Pairplot, Heatmap, KDE, etc.)

🏗️ Project Architecture

Raw Data → Data Cleaning → EDA → Visualization → Insights
📂 Dataset
Rows: 150 flowers

Columns: 5 features

Column	Description

SepalLengthCm	Sepal length (cm)

SepalWidthCm	Sepal width (cm)

PetalLengthCm	Petal length (cm)

PetalWidthCm	Petal width (cm)

Species	Flower species

✅ Balanced dataset with 50 samples per species

🛠️ Tech Stack
Language: Python 3

Libraries: Pandas, NumPy, Matplotlib, Seaborn

🔍 Analysis Workflow

1️⃣ Data Preparation
Loaded Iris.csv dataset

Removed unnecessary columns (Id)

Checked dataset info & descriptive statistics

2️⃣ Univariate Analysis
Countplot for species distribution

Histograms & Distplots for sepal/petal measurements

3️⃣ Bivariate Analysis
Jointplots (Sepal length vs width)

Scatterplots & FacetGrid by species

Strip & Swarm plots for comparing distributions

4️⃣ Multivariate Analysis
Boxplots & Violinplots for all measurements by species

Pairplot to see all relationships at once

Correlation heatmap to find feature dependencies

📊 Visualizations

✅ Countplot of species

✅ Jointplot (Sepal length vs width)

✅ FacetGrid scatterplots for species separation

✅ Box + Strip plots to visualize distributions

✅ Violin plots for detailed spread

✅ Pairplot (all numeric features vs each other)

✅ Heatmap for correlation analysis

✅ Stacked histograms & area plots

🚀 How to Run

2️⃣ Install Dependencies

pip install -r requirements.txt
3️⃣ Run Jupyter Notebook

jupyter notebook IRIS_Visualization.ipynb
4️⃣ Explore Visualizations & Insights

💡 Key Insights

Petal length & width strongly differentiate the 3 species

Iris-setosa has clearly smaller petals compared to others

Iris-virginica & Iris-versicolor overlap slightly but can still be separated with petal width

Sepal features are less effective for species separation than petals

📌 Future Enhancements

Train Machine Learning classifiers to predict species

Add Interactive Dashboards using Plotly or Streamlit

Deploy a Web App for interactive visualization


