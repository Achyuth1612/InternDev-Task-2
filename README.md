# InternDev-Task-2
Telemarketing Analysis

The code performs bank marketing campaign analysis using a Random Forest Classifier. The dataset bank-full.csv is loaded, and an initial exploration is conducted by printing the dataset's head, information, and missing values summary. Categorical columns are identified and encoded using LabelEncoder, transforming them into numeric values for machine learning compatibility. A correlation heatmap is generated to visualize relationships between features.

The target variable (y) is separated, and the data is split into training and testing sets using an 80-20 split, with stratification to preserve class distribution. The features are scaled using StandardScaler to standardize values for improved model performance.

A Random Forest Classifier with 100 estimators is trained on the scaled training data. Predictions (y_pred) and probabilities (y_prob) are obtained for the test set. Model performance is evaluated using a classification report (precision, recall, F1-score), a confusion matrix heatmap, and a ROC curve with AUC (area under the curve) for binary classification quality.

Finally, the code calculates and plots the feature importances provided by the Random Forest model, highlighting the most influential features in predicting the target variable. Visualizations, including bar plots and heatmaps, make the analysis more interpretable.
