 # 🪙 Gold Extraction ML Modeling

## 📘 Project Overview

This project dives into the gold extraction process from ore to develop a predictive machine learning model. The goal is to help Zyra optimize production by predicting the amount of gold recovered during extraction and purification stages — and ultimately eliminate unprofitable process parameters.

---

## 🎯 Objectives

- Prepare and clean the raw gold ore extraction dataset.
- Perform exploratory data analysis (EDA) on operational parameters.
- Train and evaluate multiple regression models.
- Select the best-performing model to predict gold recovery efficiency.

---

## 🧪 Dataset

The dataset includes:
- Operational parameters of gold extraction and purification.
- Target variable: amount of gold recovered at final stage.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- LightGBM
- Random Forest Regressor

---

## 📊 Modeling Workflow

1. **Data Preprocessing**  
   - Missing value imputation  
   - Feature scaling  
   - Feature selection  

2. **EDA**  
   - Distribution plots  
   - Correlation heatmaps  
   - Time-based visualizations  

3. **Modeling**  
   - Linear Regression  
   - Random Forest  
   - LightGBM  
   - Dummy Regressor for baseline  
   - Hyperparameter tuning with `GridSearchCV`  

4. **Evaluation**  
   - Mean Absolute Error (MAE)  
   - R² Score  
   - Cross-validation  

---

## 🧰 How to Run

1. **Clone the repo:**

    ```bash
    git clone https://github.com/JoeMcDow/gold-extraction-ml.git
    cd gold-extraction-ml
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Launch the notebook:**

    ```bash
    jupyter notebook notebooks/gold_extraction_modeling.ipynb
    ```

---

## 📁 Project Structure

