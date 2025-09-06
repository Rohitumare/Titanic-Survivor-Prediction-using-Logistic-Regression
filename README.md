# Titanic-Survivor-Prediction-using-Logistic-Regression

---

A beginner-friendly data analytics project that predicts Titanic passenger survival using Logistic Regression.

---

## Project Overview  
This project applies Logistic Regression to predict whether a passenger aboard the Titanic survived. It walks through the full ML pipeline—from data exploration and preprocessing to model training and evaluation—aimed at beginners looking to practice classification in Python.

---

## Repository Contents  
- `Titanic Survivors Prediction.ipynb` — Jupyter notebook detailing the full analysis and model building.  
- `Titanic-Dataset.csv` — The raw passenger data used for training and evaluation.  
- `Titanic Survivours Prediction Model 05-09-2025.pkl` — Serialized (pickled) trained Logistic Regression model for inference.

---

## Dataset  
The dataset contains passenger information such as age, gender, passenger class, fare, etc., along with the survival label. It serves as both training and testing data to evaluate the model's predictive ability.

---

## Project Workflow  

### 1. Exploratory Data Analysis (EDA)  
- Load the dataset and preview basic statistics.  
- Visualize distributions and relationships (e.g., survival rates by age, gender, fare, class).  

### 2. Data Cleaning & Preprocessing  
- Check for missing values and handle them with appropriate imputation strategies.  
- Convert categorical features (like ‘Sex’ and ‘Embarked’) into numeric format.  
- Drop irrelevant features such as `PassengerId`, `Name`, `Ticket`, and `Cabin` if present.

### 3. Feature Engineering  
- Create new meaningful features (e.g., family size from siblings/spouse and parents/children counts).  
- Normalize or scale continuous variables if needed.

### 4. Model Training & Evaluation  
- Split the data into training and testing sets.  
- Train a Logistic Regression model using the training set.  
- Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix.

---

## Results & Insights

The model's overall accuracy: 83%

### Common patterns:
- Gender: Passengers identifying as female had higher survival probability.
- Passenger Class: First-class travelers tended to survive more often.
- Age: Younger passengers generally had better chances.

---

## Conclusion

This repository demonstrates the end-to-end workflow of a Logistic Regression classification problem on a classic dataset. It’s an ideal starting point for beginners in data science and machine learning.

--- 

## Technologies Used
- Python (Pandas, NumPy, scikit-learn, Matplotlib/Seaborn)
- Jupyter Notebook
- Pickle (for model serialization)

---

## Acknowledgments & References

- Titanic dataset from Kaggle’s Titanic: Machine Learning from Disaster competition — a widely used dataset for binary classification problems (predicting survival).
- Logistic Regression is a statistical model for binary outcomes, modeling the log-odds of survival as a function of predictor variables.
