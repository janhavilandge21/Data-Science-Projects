 # 🎬 Movies Rating Analysis
📌 Project Overview
This project analyzes a dataset of 559 movies containing details like genre, critic ratings, audience ratings, budget, and year of release. The goal is to explore relationships between these variables and gain insights into how budget, genre, and year affect ratings.

The analysis uses Python, Pandas, Matplotlib, and Seaborn for data visualization and exploratory data analysis (EDA).

📂 Dataset
The dataset contains the following columns:

Column	Description
Film	Movie title
Genre	Movie genre (Action, Comedy, Drama, etc.)
CriticRating	Rotten Tomatoes Critic rating (%)
AudienceRating	Audience rating (%)
Budgetmillions	Movie budget in millions
Year	Year of release

✅ Total Rows: 559
✅ Time Period: 2007–2011
✅ Genres Covered: Action, Adventure, Comedy, Drama, Horror, Romance, Thriller

🛠️ Technologies Used
Python 3

Pandas (data handling)

NumPy (numerical operations)

Matplotlib & Seaborn (visualizations)

🔍 Analysis Performed
Data Loading & Cleaning

Loaded CSV file

Renamed columns & removed extra spaces

Converted categorical variables (Genre, Year)

Descriptive Statistics

Checked data types & missing values

Generated summary statistics

Exploratory Data Analysis (EDA)

Distribution of Audience & Critic Ratings

Movie Budget distribution

Ratings grouped by Genre

Trends over Year

Visualizations

Histograms of ratings & budgets

Jointplots showing correlations between Audience & Critic ratings

Boxplots & Violinplots comparing ratings across Genres

FacetGrid for multi-genre & year comparisons

KDE plots showing density distribution

📊 Sample Visualizations
✅ Histograms: Showed how budgets & ratings are distributed
✅ Scatterplots: Correlation between CriticRating vs AudienceRating
✅ Boxplots: Ratings comparison across Genres
✅ KDE & Violinplots: Density & spread of ratings

🚀 How to Run
pip install pandas numpy matplotlib seaborn
Run Jupyter Notebook

jupyter notebook
Open Movies_Rating_Analysis.ipynb

Explore Visualizations
Run all cells to see data insights & plots

💡 Insights & Findings
Drama & Thriller genres tend to have more budget variation

Critic Ratings have a wider range than Audience Ratings

Some high-budget movies didn’t necessarily get higher ratings

2009 saw the highest number of releases in the dataset

📌 Future Enhancements

Add Machine Learning models to predict ratings

Build an interactive dashboard with Plotly/Streamlit

Compare with box office earnings

