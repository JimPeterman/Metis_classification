# Metis_classification

The third project from my Metis Data Science Bootcamp centered around building classification models. 

I chose to build a classification model that would determine the appropriate fitness testing protocol based on features traditionally assessed before an exercise test. The goal of this classification model is to ensure accurate assessments of fitness and therefore improve patient risk stratification and patient care.

I created/tested kNN, logistic, decision tree, extra trees, random forest, naïve Bayes, and XG Boost models. Due to imbalanced groups (~10% of individuals were classified as having “low” fitness), I also explored different sampling methods (oversampling, SMOTE procedure, undersampling), different decision thresholds, and different class weights.

Model creation/testing was done with different Python libraries (SKlearn, Mlxtend, XGBoost), Pandas/Numpy for general feature engineering, and Matplotlib/Seaborn for data/model visualizations.

The finalized documents include:
- A Jupyter Notebook for the minimum viable product (MVP) assignment
- Jupyter Notebooks with the code for the project (cleaning, analysis)
- A brief writeup
- A short (5min) presentation of the project findings
