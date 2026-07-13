# Spam Email Classifier

## Objective
Classify SMS/email messages as spam or ham (not spam) using ML.

## Dataset
SMS Spam Collection Dataset (Kaggle/UCI) - 5,572 labeled messages.

## Methodology
1. Text cleaning (lowercasing, punctuation/number removal)
2. TF-IDF vectorization (max 3000 features, English stopwords removed)
3. Train/test split (80/20, stratified)
4. Trained 3 models: Naive Bayes, Logistic Regression, SVM
5. Evaluated using Accuracy, Precision, Recall, F1-score

## How to run
1. pip install pandas numpy scikit-learn matplotlib seaborn
2. Open spam_classifier_notebook.ipynb in Jupyter/Colab
3. Run all cells top to bottom

## Insights
[Write 2-3 sentences: e.g. "SVM achieved highest F1-score, indicating strong balance between catching spam and avoiding false positives. Naive Bayes was fastest to train."]
