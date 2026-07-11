
# Adult Census Income Classification

##  Project Overview
This project predicts whether an individual's annual income is **greater than $50K** or **less than or equal to $50K** using machine learning classification algorithms. The project includes data preprocessing, model training, and performance evaluation.

##  Dataset
- **Dataset:** Adult Census Income Dataset
- **Source:** Kaggle
- **Target Variable:** Income (`<=50K` or `>50K`)

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

##  Data Preprocessing
- Loaded the dataset
- Handled missing values
- Removed unnecessary records
- Encoded categorical variables
- Selected relevant features
- Split the dataset into training and testing sets

##  Machine Learning Models
- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression

##  Model Evaluation
The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

##  Project Structure
```
Adult-Census-Income-Classification/
│── Adult_Census_Income_Classification.ipynb
│── README.md
│── requirements.txt
```

##  How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook.
4. Run all cells to reproduce the results.

##  Objective
The objective of this project is to compare different machine learning classification algorithms and evaluate their performance in predicting adult income levels.

##  Future Improvements
- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Additional classification models (XGBoost, SVM, KNN)

##  Author
**Delisha Shibu**
