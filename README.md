# 🎬 Budget vs Gross Correlation in Movies  
This project explores the correlation between a film's budget and its gross earnings, using Python libraries such as pandas, numpy, matplotlib, and seaborn. It includes data preprocessing, exploratory analysis, visualizations, and statistical correlation interpretation.

📊 Objective  
To understand the relationship between production budget and revenue in the movie industry. By identifying correlations, we aim to answer whether higher budgets generally result in higher gross earnings.  

🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
  
🧹 Data Cleaning Steps  
- Loaded the movie dataset from CSV  
- Removed rows with missing values in critical columns like budget and gross  
- Converted numerical columns to appropriate int64 types  
- Extracted release year from the full date string in the released column  
  
🔍 Key Insights  
- Strong positive correlation (0.74) between budget and gross, as visualized in the heatmap
- Other features like votes and score also show moderate correlation with gross
- Helps reinforce the hypothesis that bigger budgets often lead to higher revenue—but with exceptions
  
🗂️ Dataset  
Movies [dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies) used contains features such as:
- name, genre, rating, budget, gross, votes, score, runtime, etc.


