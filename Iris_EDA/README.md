Iris Dataset – Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs exploratory data analysis (EDA) on the classic Iris dataset, one of the most well-known datasets in data science.
The goal is to understand the structure of the dataset, visualize feature distributions, analyze correlations, and compare characteristics of different species.

📂 Project Files

Iris_EDA.ipynb → Jupyter Notebook with EDA steps

Iris_Analyzed.csv → Processed dataset with insights

README.md → Project documentation

⚙️ Tools & Libraries

Python (Pandas, Seaborn, Matplotlib)

Jupyter Notebook / Google Colab

Dataset: Iris (built-in via seaborn.load_dataset("iris"))

🔍 Steps Performed

Data Exploration → Checked dataset info, shape, and summary statistics.

Distribution Analysis → Visualized histograms for numerical features.

Pairwise Analysis → Created scatter plots to explore relationships between variables.

Correlation Analysis → Heatmap to check feature correlations.

Boxplots by Species → Compared feature distributions across Iris species.

Summary Insights → Documented key findings.

📊 Sample Insights

✅ Dataset has 150 rows and 5 columns (4 numerical features + 1 categorical species).

✅ Three species: Setosa, Versicolor, Virginica.

✅ Petal length and width are strongly correlated (0.96).

✅ Setosa species has distinctly smaller petals compared to Versicolor and Virginica.

✅ Sepal features overlap more across species compared to petal features.

🚀 How to Run

Clone this repo:

git clone https://github.com/<your-username>/Ayansh-Data-Analytics-Portfolio.git
cd Ayansh-Data-Analytics-Portfolio/Iris_Project


Open Jupyter Notebook or Google Colab.

Run all cells in Iris_EDA.ipynb.

🏆 Skills Demonstrated

Exploratory Data Analysis (EDA)

Data Visualization (Seaborn, Matplotlib)

Correlation Analysis & Feature Insights

Python (Pandas, Seaborn)

📌 Next Steps

Use EDA results for classification modeling (Logistic Regression, Decision Trees).

Compare accuracy of models with petal vs. sepal features.
