# Restaurant Cuisine Classification

## Overview
This project is part of my internship at **Cognifyz Technologies**. The objective is to develop a **machine learning model** to classify restaurants based on their cuisines using **natural language processing (NLP)** techniques.

## Dataset
The dataset contains restaurant details, including:
- Restaurant Name
- Cuisines
- City
- Locality

The primary goal is to classify restaurants into different cuisine categories based on the provided textual data.

## Steps Involved

### 1. Data Preprocessing
- Handling missing values
- Extracting primary cuisine type
- Encoding categorical variables

### 2. Feature Engineering
- Combining restaurant-related text data
- Applying **TF-IDF vectorization** for text representation

### 3. Model Training & Evaluation
- **Logistic Regression**
- **Random Forest Classifier**
- Evaluation metrics: **Accuracy, Precision, Recall, F1-score**

### 4. Model Interpretation & Improvements
- Analyzing feature importance
- Handling class imbalance with **SMOTE**
- Comparing different model performances

## Results
Both Logistic Regression and Random Forest classifiers were trained and evaluated. The results show promising accuracy in predicting the correct cuisine type based on restaurant data.

## Live Notebook
You can check the complete implementation in Google Colab:  
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iK6eibpyrLsR9YcjXg5BWuHE0JacRtSS?usp=sharing)

## GitHub Repository
You can find the complete project code here:  
[Restaurant Cuisine Classification](https://github.com/mmanikandan281/Restaurant-Cuisine-Classification.git)

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/mmanikandan281/Restaurant-Cuisine-Classification.git
   ```


## Developed By
**Manikandan M**  


## Acknowledgments
- **Cognifyz Technologies** for providing this opportunity
- Open-source libraries: **Pandas, Scikit-learn, Matplotlib, Seaborn**

Thank you! 🚀
