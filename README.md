# IRIS-Classification-Dataset
✨ I implemented the Iris classification task myself, and my version goes beyond the one in the PDF. Their version mainly used LabelEncoder/MinMaxScaler, separate steps, and focused on Logistic Regression with lots of visualizations. Mine is different: I built a proper ML pipeline with ColumnTransformer (StandardScaler + OneHotEncoder), compared three models (Logistic Regression, Random Forest, Decision Tree), and tuned hyperparameters using GridSearchCV. I reported CV score, best params, classification report, and test accuracy — so it’s structured, reusable, and closer to how ML is done in production.

The major difference is that their version is more exploratory with plots, while mine is engineering‑oriented with pipelines and metrics. I focused on numbers because that’s how I understand results best, even though I’m still improving at visualization. I’ve studied ML thoroughly during this internship, and this project reflects that learning.

Dataset
https://www.kaggle.com/datasets/bhanupratapbiswas/iris-classification-dataset
