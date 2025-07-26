# Big-Data-Analysis-and-Project
Assignment 1 Part B
The libraries used in this project are- 
1. Pandas- Pandas is used for data manipulation and analysis
2. Numpy- It is used for numerical operations
3. Matplotlib.pyplot- This library is used for plotting visualizations
4. Seaborn- It is used for advanced statistical visualizations
5. Sklearn.preprocessing- From this StandardScaleris used to normalize the data. 
6. Sklearn.impute- This library is used for handling missing values.
7. Sklearn.decomposition - Used for PCA for dimensionality reduction
8. Sklearn.cluster - To apply clustering algorithms like KMeans and Hierarchical Clustering
9. Sklearn.mixture - For GaussianMixture model

Steps
1. First of all the dataset is loaded using Pandas
2. Dataset shape, Missing values, class distribution and feature summary are checked which are called Exploratory Data Analysis (EDA)
3. Clustering Techniques like K-Means, Gaussian Mixture Model (GMM) and Hierarchical Clustering are applied Each of them have cluster visualisation and cluster statistics.
4. Visualisations techniques were applied. Correlation Matrix and Heatmap, Pie-Chart, Box-plot and various Histograms of features.

Assignment 1 Part C
The libraries used in this project are- 
1. Pandas - Used for data loading, manipulation, and analysis.
2. Numpy – Used for numerical operations.
3. Matplotlib.pyplot – This library is used for plotting visualizations.
4. Seaborn – It is used for advanced statistical visualizations.
5. Sklearn.preprocessing – Used for scaling (StandardScaler) and encoding (OrdinalEncoder).
6. Sklearn.decomposition – Used for PCA for dimensionality reduction.
7. Sklearn.linear_model – For applying Logistic Regression.
8. Sklearn.svm- For applying Support Vector Machine (SVM).
9. Sklearn.neural_network – For applying Multilayer Perceptron (MLP) model.
10. Sklearn.ensemble – For applying Random Forest model.
11. XGBoost – For applying XGBoost Classifier model.
12. Sklearn.model_selection – For train-test split and GridSearchCV.
13. Sklearn.metrics – For classification report, confusion matrix, accuracy score, ROC-AUC score, ROC curve.
14. Sklearn.multiclass – For using OneVsRestClassifier.
15. Imblearn.combine – SMOTETomek used to handle class imbalance.

Steps
1. The dataset is loaded using Pandas.
2. Ordinal Encoding is applied to ordered categorical features using OrdinalEncoder.
3. Class imbalance is handled using SMOTETomek technique from the imblearn library.
4. Dataset is split into training and testing sets using train_test_split. 80% is used for training and 20% is used for testing
5. StandardScaler is applied to normalize feature values.
6. Baseline Logistic Regression is trained. Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess model performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
7. GridSearchCV is used for hyperparameter tuning for Logistic Regression. Then for best hyperparameter tuned setting Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
8. Baseline Random Forest is trained. Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess model performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
9. GridSearchCV is used for hyperparameter tuning for Random Forest. Then for best hyperparameter tuned setting Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
10. Baseline Support Vector machine is trained. Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess model performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
11. GridSearchCV is used for hyperparameter tuning for Support Vector Machine. Then for best hyperparameter tuned setting Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
12. Baseline XGBoost is trained. Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess model performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
13.  GridSearchCV is used for hyperparameter tuning for XGBoost. Then for best hyperparameter tuned setting Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
14.  Baseline Multilayer Perceptron is trained. Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess model performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.
15.   GridSearchCV is used for hyperparameter tuning for Multilayer Perceptron. Then for best hyperparameter tuned setting Evaluation metrics like Accuracy, Confusion Matrix, Classification Report, and ROC-AUC Curve are used to assess performance. Visualisation techniques were applied. ROC-AUC curves, Confusion Matrix Heatmaps, and other plots were generated to interpret results.







   
