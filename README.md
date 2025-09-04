# CodeAlpha_IrisClassification
Iris Flower Classification using Machine Learning | CodeAlpha Internship Task 1
# CodeAlpha_IrisClassification

##Project Overview
This project is part of my **CodeAlpha Data Science Internship**.  
The goal is to classify **Iris flowers** (Setosa, Versicolor, Virginica) based on sepal and petal measurements.

#Dataset
Dataset: [Iris Dataset on Kaggle](https://www.kaggle.com/datasets/saurabh00007/iriscsv)  
Features: Sepal Length, Sepal Width, Petal Length, Petal Width  
Target: Species (Setosa, Versicolor, Virginica)  

#Models Used
Logistic Regression  
Decision Tree  
Random Forest  
Support Vector Machine (SVM)  

#Results
Logistic Regression CV Accuracy: **0.97**  
Decision Tree CV Accuracy: **0.95**  
Random Forest CV Accuracy: **0.97**  
SVM CV Accuracy: **0.90**  

All models initially showed 100% accuracy on a single test split due to the clean dataset.  
Cross-validation provided more realistic results.  
Random Forest and Logistic Regression performed best overall.  

#Tools & Libraries
Python  
Pandas, NumPy
Scikit-learn  
Seaborn, Matplotlib  
#Conclusion
The Iris dataset is small and clean, making it easy to classify with simple machine learning models.  
This project helped me understand the basics of **classification, model evaluation, and cross-validation**.  
