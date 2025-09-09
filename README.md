# Planetary Classifier

This project builds a machine learning classifier to predict planetary classes based on various planetary features such as Atmospheric Density, Gravity, Surface Temperature, etc.


## Problem Statement
The goal is to automate the classification using machine learning models.



## Approach

1. **Data Preprocessing:**  
    - Fill missing numerical and categorical values.  
    - One-hot encode categorical features.  
    - Scale numerical features using StandardScaler.  
    - Split data into training (80%) and testing (20%) sets.

2. **Model Training:**  
    - Random Forest Classifier  
    - Logistic Regression  

3. **Evaluation Metrics:**  
    - Accuracy  
    - Precision  
    - Recall  
    - F1 Score  

4. **Feature Importance:**  
    - Visualized top contributing features using Random Forest.


##  Conclusion

- Both Random Forest and Logistic Regression performed similarly with ~86% accuracy.  
- Random Forest is preferred for its ability to handle non-linear patterns and provide feature importance insights.


## Dataset

The dataset used is named `cosmicclassifierTraining.csv` and contains multiple features describing planetary conditions along with the target column `Prediction`.


## Link to Notebook

You can find the full working notebook here:  [
https://github.com/Ishika-Pattnaik/Planetary-classifier/blob/main/ML_task1.ipynb](https://colab.research.google.com/drive/1X5kToXpkoI0v_soA6ipsIq3ed0IYcphm?usp=sharing)


Made with ❤️ by [Ishika Pattnaik]

