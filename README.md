# Diabetes Prediction Using Machine Learning (Ensemble Models)

This project focuses on predicting whether a person is diabetic using ensemble machine learning techniques. It uses the Pima Indians Diabetes dataset to demonstrate how models like Random Forest, Gradient Boosting, and other ensemble methods can be applied to a real-world health prediction problem.

---

## Project Structure

├── Diabetics_Ensemble.ipynb # Main notebook for data processing and prediction
├── README.md # Project description and usage guide

    
---

## Machine Learning Models Used

The project leverages the power of ensemble learning to increase prediction accuracy. Models used include:

- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost
- Voting Classifier (combining multiple models)

---

## Dataset

The notebook uses the Pima Indians Diabetes Dataset, which contains diagnostic measurements like:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) or use the preloaded one in the notebook.

---

## Workflow

1. Data Loading – Import the dataset.
2. Preprocessing – Handle missing values and perform scaling if required.
3. Exploratory Data Analysis (EDA) – Understand feature importance and distribution.
4. Model Training – Train multiple ensemble classifiers.
5. Model Evaluation – Accuracy, precision, recall, and ROC-AUC.
6. Voting Classifier – Combine top-performing models.

---

## Results

- Accuracy scores of individual models are compared.
- Final predictions are made using the Voting Classifier for robust performance.

---

## Requirements

Install required libraries with:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
Run the Notebook
To run this project:

Clone the repository or download the notebook.

Open Diabetics_Ensemble.ipynb in Jupyter Notebook or Google Colab.

Run the cells step-by-step.

Applications
Clinical Decision Support Systems (CDSS)

Preventive healthcare diagnosis

Healthcare analytics and data science learning

Author
