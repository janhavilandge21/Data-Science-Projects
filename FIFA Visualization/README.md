# ⚽ FIFA Dataset Visualization
📌 Project Overview
This project performs extensive data visualization on the FIFA 19 dataset using Seaborn & Matplotlib. It explores player attributes such as age, potential, overall rating, preferred foot, and international reputation, providing insights into player distributions and patterns.

✅ Univariate, Bivariate & Multivariate analysis

✅ Visualizing categorical & numerical features

✅ Exploring relationships between ratings & attributes

🏗️ Project Workflow

Raw FIFA Data → Data Cleaning → Visualization → Insights
📂 Dataset
Rows: 18,207 players

Columns: 89 features

Key attributes:

Column	Description

Name	Player name

Age	Player age

Nationality	Country

Overall	Overall rating

Potential	Player potential

Preferred Foot	Left/Right

International Reputation	Reputation score (1-5)

Height, Weight	Physical attributes

Club, Value, Wage	Contract details


🛠️ Tech Stack
Language: Python 3

Libraries: Pandas, NumPy, Matplotlib, Seaborn

🔍 Analysis Performed

1️⃣ Data Preparation

Loaded FIFA.csv

Checked missing values

Explored column datatypes & unique values

2️⃣ Univariate Analysis

Distribution of age, potential, overall ratings

Countplots for Preferred Foot, Body Type, International Reputation

3️⃣ Bivariate Analysis

Height vs Weight scatterplots

Overall vs Potential regression plots

Preferred Foot vs International Reputation vs Potential

4️⃣ Multivariate Analysis

FacetGrid plots for Preferred Foot categories

PairGrid plots for Age, Strength, Stamina, Potential

Jointplots & KDE plots for continuous attributes

📊 Visualizations

✅ Histograms & KDE plots for age, potential, overall

✅ Boxplots & Violinplots for preferred foot vs potential

✅ Countplots for categorical features like preferred foot & reputation

✅ FacetGrid & PairGrid for multi-feature visualization

✅ Jointplots & lmplots for regression analysis

✅ Scatterplots for Height vs Weight

✅ Barplots & Pointplots for potential vs reputation

🚀 How to Run


2️⃣ Install Dependencies

pip install -r requirements.txt
3️⃣ Run Jupyter Notebook


jupyter notebook FIFA_Visualization.ipynb
4️⃣ Explore the visualizations

💡 Key Insights
Right-footed players dominate (~77%)

Most players have international reputation = 1

Younger players tend to have higher potential than older ones

High potential correlates strongly with high overall ratings

Messi, Ronaldo, and Neymar top the potential & reputation charts

📌 Future Enhancements

Build ML models to predict player potential

Create an interactive dashboard using Plotly/Streamlit

Perform clustering to find similar players
