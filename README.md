# 📈 Heart Failure Prediction and Clinical Record Analysis

![Python Badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook Badge](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas Badge](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy Badge](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib Badge](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn Badge](https://img.shields.io/badge/Seaborn-228B22?style=for-the-badge&logo=seaborn&logoColor=white)
![Scikit-learn Badge](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Decision Tree Badge](https://img.shields.io/badge/Algorithm-Decision%20Tree-blue?style=for-the-badge)
![KNN Badge](https://img.shields.io/badge/Algorithm-KNN-lightgrey?style=for-the-badge)

## 💡 Overview

This project focuses on **predicting heart failure events** using clinical records data and various machine learning classification techniques. Developed as an assignment for a data science unit at RMIT University, this project demonstrates a complete data science workflow, from data preparation and exploratory data analysis (EDA) to model building, evaluation, and insightful reporting.

The primary goal was to identify the most important attributes influencing heart failure and to build a robust predictive model. The project compares the performance of Decision Tree and K-Nearest Neighbors (KNN) algorithms on the given dataset.

## ✨ Project Phases & Key Findings

### 1. Data Preparation and Cleaning
* **Dataset Selection:** Utilized the "Heart Failure Clinical Records Dataset," comprising 13 attributes and 299 instances, with `DEATH_EVENT` as the target variable.
* **Quality Assurance:** Confirmed the absence of missing values. Addressed minor inconsistencies (e.g., decimal points in the `age` column) to ensure data integrity.

### 2. Exploratory Data Analysis (EDA)
* **Descriptive Statistics:** Performed statistical analysis on all attributes to understand their distribution and characteristics.
* **Data Visualization:** Employed `Matplotlib` and `Seaborn` to visualize key relationships and patterns within the data.
* **Feature Importance Exploration:** Investigated significant relationships between attributes like `serum_creatinine`, `ejection_fraction`, and the `DEATH_EVENT`, identifying them as strong predictors.

### 3. Data Modeling and Evaluation
* **Model Selection:** Implemented and evaluated two classification algorithms:
    * **Decision Tree Classifier:** Explored various tree depths and parameters. Achieved an optimal accuracy of **73.33%** with entropy criterion and a max depth of 3, indicating strong predictive power for this dataset.
    * **K-Nearest Neighbors (KNN) Classifier:** Tested different values of K to find the best performing neighbor count. Achieved an accuracy of **56.67%**.
* **Model Comparison:** Concluded that the Decision Tree model significantly outperformed the KNN model for this prediction task.
* **Performance Metrics:** Utilized `accuracy_score` and `confusion_matrix` for comprehensive model evaluation. Generated confusion matrices for both models to understand true positives, true negatives, false positives, and false negatives.

## 🚀 Technologies Used

* **Python:** Core programming language for data analysis and machine learning.
* **Jupyter Notebook:** Interactive environment for data exploration, coding, and documentation.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations and array handling.
* **Matplotlib:** For creating static, interactive, and animated visualizations in Python.
* **Seaborn:** Built on Matplotlib, providing a high-level interface for drawing attractive statistical graphics.
* **Scikit-learn:** Comprehensive library for machine learning, including:
    * `DecisionTreeClassifier`
    * `KNeighborsClassifier`
    * `train_test_split`
    * `accuracy_score`
    * `confusion_matrix`, `ConfusionMatrixDisplay`

## 🛠️ Installation & Setup

To run this analysis locally, you will need Python and the specified libraries.

### Prerequisites

* Python 3.x
* `pip` (Python package installer)

### Steps

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Jagulan/Data_science_with_python_A2.git](https://github.com/Jagulan/Data_science_with_python_A2.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Data_science_with_python_A2
    ```
3.  **Install the required Python libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  **Open the Notebook:** In the Jupyter interface, open `Assignment2.ipynb`.
6.  **Run Cells:** Execute the cells sequentially to perform the data loading, cleaning, EDA, model training, and evaluation. Ensure `heart_failure_clinical_records_dataset.csv` is in the same directory as the notebook.

## 📊 Reports & Results

This repository includes a detailed PDF report (`report.pdf`) that summarizes the project's methodology, findings, and conclusions. Key results highlighted in the report include:

* **Decision Tree Model Accuracy:** 73.33% with optimized parameters (entropy criterion, max depth 3).
* **K-Nearest Neighbors Model Accuracy:** 56.67%.
* **Conclusion:** Decision Tree is identified as the superior classification model for this dataset, with `serum_creatinine` and `ejection_fraction` being crucial predictive features.
## 📞 Contact

Feel free to reach out if you have any questions or want to discuss this project further!

* **LinkedIn:** [linkedin.com/in/jagulans](https://linkedin.com/in/jagulans)
* **Email:** `gsjagulan@outlook.com`
