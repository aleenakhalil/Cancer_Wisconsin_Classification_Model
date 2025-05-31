# Cancer_Wisconsin_Classification_Model

## Project Overview
This project focuses on building and comparing classification models using the Breast Cancer Wisconsin dataset. The objective is to predict whether a tumor is malignant or benign based on various cellular features. Two popular classification algorithms—Logistic Regression and Random Forest—are trained, evaluated, and compared using metrics like accuracy and F1 score.

## Dataset
The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset, available here: https://drive.google.com/file/d/1TQDAoNFJ7DtsneYGt83nrd7HEnQOtCjB/view

## Key Insights

### Data Cleaning & Preprocessing
1. Removed irrelevant columns (id and unnamed column).
2. Encoded the target variable 'diagnosis' into numerical values (M=0, B=1).
3. Verified no missing values were present.
4. Features and target were separated for modeling.
5. Performed train-test split (80-20).
6. Scaled features only for Logistic Regression using StandardScaler to normalize data.

### Model Training & Evaluation
1. Built two models:
- Logistic Regression: Used scaled features for training.
- Random Forest: Used original features without scaling.

2. Evaluated models using:
- Accuracy
- F1 Score
- Classification Report
- Confusion Matrix (visualized via heatmaps)

3. Compared models side-by-side with bar charts for accuracy and F1 score.

4. Visualizations Created
- Confusion matrix heatmaps for each model showing true vs predicted labels.
- Bar chart comparing accuracy and F1 score for Logistic Regression and Random Forest.


## Tools and Libraries Used
- Pandas
- Matplotlib
- SeabornScikit-learn
- Jupyter Notebook / Google Colab
