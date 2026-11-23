# Multi-class Benchmark Classification Pipeline (Iris Dataset) 

This repository contains **Task 1** of the **Datheon Machine Learning Internship**, focusing on building a structured, end-to-end multi-class classification pipeline using the classic **Iris Dataset**.

## 📌 Project Overview
The objective of this project is to explore, preprocess, and classify iris flower species (`setosa`, `versicolor`, and `virginica`) based on four morphological features (`sepal_length`, `sepal_width`, `petal_length`, `petal_width`). It benchmarks the performance of foundational supervised machine learning algorithms.

## 🛠️ Technologies & Libraries Used
* **Data Manipulation & Analysis:** `NumPy`, `Pandas`
* **Data Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning & Preprocessing:** `Scikit-Learn` (`StandardScaler`, `train_test_split`, `LogisticRegression`, `DecisionTreeClassifier`, and evaluation metrics)

## 🔄 Pipeline Workflow
1. **Data Loading & Inspection:** Loaded `iris.csv` (150 samples, 5 columns) and verified data types and missing values (0 null values).
2. **Exploratory Data Analysis (EDA):**
   * Generated descriptive statistical summaries (mean, std, min, max, quartiles).
   * Plotted exploratory `pairplots` colored by species to visualize feature distributions and class separability.
3. **Data Preprocessing:**
   * Feature scaling using `StandardScaler`.
   * Splitting the dataset into training and testing sets via `train_test_split`.
4. **Model Training & Benchmarking:**
   * **Logistic Regression**
   * **Decision Tree Classifier**
5. **Model Evaluation:** Evaluated and compared model performance using **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **Confusion Matrices**.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/JosephBotros47/Datheon-Machine_learning-Internship-Multi-class_Benchmark_classification_pipline.git](https://github.com/JosephBotros47/Datheon-Machine_learning-Internship-Multi-class_Benchmark_classification_pipline.git)
