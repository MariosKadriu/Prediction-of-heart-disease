# Prediction of heart disease

## Table of Contents

[Description](https://github.com/MariosKadriu/Prediction-of-heart-disease#-description)
 
[Dataset](https://github.com/MariosKadriu/Prediction-of-heart-disease#-dataset)

[Installation](https://github.com/MariosKadriu/Prediction-of-heart-disease#%EF%B8%8F-installation)

[Exploratory Data Analysis](https://github.com/MariosKadriu/Prediction-of-heart-disease#-exploratory-data-analysis)

[Modeling and Evaluation](https://github.com/MariosKadriu/Prediction-of-heart-disease#-modeling-and-evaluation)

## 📝 Description

The above project was implemented with the aim of predicting the heart disease by modelling and evaluating machine learning algorithms
as well as exploring data on: 
* Heart disease frequency according to sex
* Heart Disease in function of Age and Max Heart Rate
* Heart Disease Frequency per Chest Pain Type


## 📚 Dataset

The dataset used can be found here: https://github.com/MariosKadriu/Prediction-of-heart-disease/blob/master/heart-disease.csv

## 🖥️ Installation

### 🛠️ Requirements
* Python >= 3.6
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

### ⚙️ Setup

All of the above packages can be installed from the following commands.

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install -U scikit-learn

```

## 🔍 Exploratory Data Analysis

### Check for class imbalance between two classes

![download](https://user-images.githubusercontent.com/19438003/191215431-f133f1ca-ee6c-4382-90fd-ae41780b3711.png)

### Heart Disease Frequency For Sex

![image-2](https://user-images.githubusercontent.com/19438003/191216178-2ba77b3c-92a8-4ff8-91f7-0bc13e4e2fd4.png)

### Age and Max Heart Rate for Heart Disease

![image-3](https://user-images.githubusercontent.com/19438003/191216510-d36a41ac-e6d1-4124-b05d-7f1d5d4d46f4.png)

### Distribution of the age using histogram
![image-4](https://user-images.githubusercontent.com/19438003/191216772-99ad0d7d-585d-49d3-886c-aae08c614326.png)

### Heart Disease Frequency per Chest Pain Type
![image-5](https://user-images.githubusercontent.com/19438003/191216882-8f1bf428-6cea-45d3-b514-a896748a0a1c.png)

### Correlation between features
![image-6](https://user-images.githubusercontent.com/19438003/191217126-103e5832-d701-464c-8096-d88fa8886c3f.png)

## 🎯 Modeling and Evaluation

### Models

* Logistic Regression
* K-nearest Neighbors
* Random Forest

### Evaluation Metrics

* Accuracy, Precision, Recall, F1-Score
* ROC Curve
* Confusion Matrix

### Model Comparison
![image-7](https://user-images.githubusercontent.com/19438003/191218359-e362d66c-186e-4e09-b5d1-958d11b80522.png)

### Hyperparameter tuning (by hand) using K-nearest Neighbors
![image-8](https://user-images.githubusercontent.com/19438003/191218752-53294437-dd9b-4b4e-a3e4-c6d46bcc1245.png)

### Evaluting the tuned machine learning classifier, beyond accuracy
![image-9](https://user-images.githubusercontent.com/19438003/191219081-758304c1-62ac-46ec-8c9d-02b1be40a24e.png)

### Confusion Matrix
![image-10](https://user-images.githubusercontent.com/19438003/191219279-ebd00d84-bcb1-4237-94ac-224f98778069.png)

### Calculation of evaluation metrics using cross-validation
![image-11](https://user-images.githubusercontent.com/19438003/191219452-4c4332ad-9206-405e-9a48-f49e9d53819f.png)

### Feature Importance
![image-12](https://user-images.githubusercontent.com/19438003/191219670-f2759c90-3507-4752-843d-5c1cc8f786eb.png)
