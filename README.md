# Decision-Trees-and-Random-Forests--Task-5
What was done:
- EDA: head, info, missing values, summary stats, target distribution, correlation matrix.
- Train/test split with stratify, scaler fitted on training data only.
- Baseline Decision Tree followed by overfitting analysis across max_depth values.
- GridSearchCV to pick best max_depth (5-fold CV).
- Trained a tuned Decision Tree and Random Forest (n_estimators=100).
- Compared accuracies, displayed classification reports, and confusion matrix.
- Feature importances from Random Forest (csv + plot).
- 5-fold cross-validation on Random Forest.
  Notes:
- StandardScaler was applied only to numeric columns and was fit on the training set only.
- Visualizations use Matplotlib only for portability (no Graphviz or seaborn dependencies).
"""
