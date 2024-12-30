# Heart Disease Prediction with Machine Learning

This repository contains a Python-based implementation of machine learning models to predict heart disease. The project utilizes multiple algorithms, including Logistic Regression, Decision Trees, and Support Vector Machines (SVM), to classify data from a heart disease dataset.

## Dataset
The dataset used in this project is named `heart.csv`, which contains the following key features:

- `age`: Age of the patient
- `sex`: Gender of the patient (1 = male, 0 = female)
- `cp`: Chest pain type
- `trtbps`: Resting blood pressure (in mm Hg)
- `chol`: Cholesterol levels (mg/dl)
- `fbs`: Fasting blood sugar (>120 mg/dl, 1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results
- `thalachh`: Maximum heart rate achieved
- `exng`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slp`: The slope of the peak exercise ST segment
- `caa`: Number of major vessels (0-3)
- `thall`: Thalassemia status
- `output`: Target variable (1 = heart disease present, 0 = not present)

## Features

- **Data Exploration**: Examines the structure of the dataset and provides value counts for each feature.
- **Preprocessing**:
  - Converts specific columns (e.g., `oldpeak`) to integers.
  - Splits the data into training and testing sets.
- **Model Training and Evaluation**:
  - Logistic Regression: Predicts target values and evaluates performance using metrics like Jaccard Index, Log Loss, and Classification Reports.
  - Decision Tree: Constructs a decision tree classifier and evaluates its accuracy.
  - SVM: Implements a Support Vector Classifier with linear kernel and assesses its performance.
- **Visualization**:
  - Confusion matrices for each model to visualize prediction results.
  - Decision tree structure exported and displayed as an image.

## Requirements
- Python 3.7+
- Required libraries:
  ```bash
  pip install pandas numpy matplotlib scikit-learn pydotplus
  ```

## Results
The performance of the models is evaluated using metrics such as accuracy, Jaccard Index, Log Loss, and classification reports. The confusion matrices provide insights into the true positive and negative rates.

## Visualization Example
### Decision Tree Structure
![Decision Tree](HeartAttack.png)

### Confusion Matrix
A sample confusion matrix is plotted for each model to compare predicted vs actual outcomes.

## Future Work
- Include additional feature engineering techniques to improve model performance.
- Explore advanced machine learning algorithms like Random Forests and Neural Networks.
- Perform hyperparameter tuning for better optimization.
