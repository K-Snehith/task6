# Task 6 - K-Nearest Neighbors (KNN) Classification

## 🎯 Objective
Use KNN to classify flower types in the Iris dataset and visualize decision boundaries.

## 📁 Dataset
- Dataset: Iris (from `sklearn.datasets.load_iris`)

## 🛠 Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## 📚 Steps Performed
1. Loaded the Iris dataset using sklearn
2. Normalized features using StandardScaler
3. Trained `KNeighborsClassifier` with different k values: 1, 3, 5, 7
4. Evaluated using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
5. Visualized decision boundaries using only 2 features

## 📈 Sample Output

✅ Dataset loaded:
   sepal length (cm)  sepal width (cm)  ...  petal width (cm)  target
0                5.1               3.5  ...               0.2       0
1                4.9               3.0  ...               0.2       0
2                4.7               3.2  ...               0.2       0  
3                4.6               3.1  ...               0.2       0  
4                5.0               3.6  ...               0.2       0  

[5 rows x 5 columns]

🔢 K = 1
Accuracy: 0.9666666666666667
Confusion Matrix:
 [[10  0  0]
 [ 0  8  1]
 [ 0  0 11]]
Classification Report:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      0.89      0.94         9
           2       0.92      1.00      0.96        11

    accuracy                           0.97        30
   macro avg       0.97      0.96      0.97        30
weighted avg       0.97      0.97      0.97        30


🔢 K = 3
Accuracy: 1.0
Confusion Matrix:
 [[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
Classification Report:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30


🔢 K = 5
Accuracy: 1.0
Confusion Matrix:
 [[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
Classification Report:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30


🔢 K = 7
Accuracy: 1.0
Confusion Matrix:
 [[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
Classification Report:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30

✅ Press Enter to exit...
