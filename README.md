# Machine Learning Project: FoodHub Data Analysis and Prediction

This project presents a complete machine learning pipeline developed in **Google Colab** using the FoodHub dataset. It involves end-to-end steps from exploratory data analysis (EDA) to model building and evaluation for both **regression** and **classification** tasks.

---

## 📁 Project Structure

### 1. EDA (Exploratory Data Analysis)
- Checked missing values and data types
- Visualized categorical and numerical features
- Outlier detection using boxplots

### 2.  Data Preprocessing
- Label encoding & one-hot encoding
- Feature scaling (StandardScaler, MinMaxScaler)

### 3. Train-Test Split
- Used `train_test_split()` for regression & classification tasks

### 4.  Model Building

####  Regression Models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

####  Classification Models:
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

### 5. Model Evaluation

#### Regression:
- MAE, MSE, RMSE, R² Score

#### Classification:
- Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

##  Technologies Used

- Python (in Google Colab)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost (if used)

---

##  Files in this Repository

| File Name           | Description                                 |
|---------------------|---------------------------------------------|
| `foodhub_ml.ipynb`  | Main Colab notebook for the entire project  |
| `dataset.csv`       | Dataset used (if uploaded)                  |
| `model.pkl`         | Trained model (if saved)                    |
| `README.md`         | Project documentation                       |

---

##  How to Run the Project

1. Open the notebook in Google Colab
2. Upload the dataset (if not embedded)
3. Run the code cells step-by-step
4. Check evaluation metrics and model output

---

**Surbhi Keshari**  
B.Tech CSE (AI & ML) – 2nd Year  
Summer Internship Project, 2025

