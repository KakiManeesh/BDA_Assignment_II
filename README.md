# Big Data Analytics using PySpark

This project demonstrates the use of PySpark for performing classification, clustering, and recommendation tasks on real-world datasets. The notebook covers the complete workflow including data preprocessing, model building, evaluation, and visualization.

> Note: This project is designed to run in Google Colab. All datasets are downloaded dynamically during execution and are not stored in this repository.

---

## Overview

The project includes three main tasks:

- Classification using Logistic Regression on the Titanic dataset  
- Clustering using K-Means on the Iris dataset  
- Recommendation system using ALS on the MovieLens dataset  

---

## Technologies Used

- Python  
- PySpark (MLlib)  
- Pandas  
- Matplotlib  

---

## Tasks Implemented

### 1. Classification (Titanic Dataset)

- Dataset loaded from:  
  https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv  

- Selected features: Pclass, Sex, Age, Fare  
- Handled missing values  
- Converted categorical data using StringIndexer  
- Built Logistic Regression model  

**Evaluation Metrics:**
- Accuracy  
- F1 Score  
- Precision  
- Recall  

**Visualization:**
- Confusion Matrix  
- Scatter Plot (Age vs Fare)  

---

### 2. Clustering (Iris Dataset)

- Dataset loaded from:  
  https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv  

- Feature vector created using VectorAssembler  
- Applied K-Means clustering (k = 3)  

**Evaluation:**
- Silhouette Score  

**Visualization:**
- Cluster scatter plot (Sepal Length vs Petal Length)  

---

### 3. Recommendation System (MovieLens Dataset)

- Dataset downloaded using:
- wget https://files.grouplens.org/datasets/movielens/ml-100k.zip
- unzip ml-100k.zip
- 
- Used ALS (Alternating Least Squares) for collaborative filtering  

**Evaluation:**
- RMSE (Root Mean Squared Error)  

**Output:**
- Top movie recommendations for users  
- Ratings distribution histogram  

---

## Visualizations

- Confusion Matrix for classification results  
- Scatter plots for feature relationships  
- Cluster visualization  
- Ratings distribution histogram  

---

## How to Run

1. Open the notebook in Google Colab  
2. Ensure PySpark environment is available  
3. Run all cells sequentially  
4. All datasets will be downloaded automatically during execution  

---

## Key Learning Outcomes

- Understanding PySpark ML pipeline  
- Working with distributed datasets  
- Implementing classification, clustering, and recommendation systems  
- Evaluating machine learning models  
- Data visualization techniques  
