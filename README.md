# 🔍 Student Performance Prediction - Regression Analysis with Random Forest

This project performs regression analysis on a dataset (`ResearchInformation3.csv`) using **Random Forest Regressor**. It aims to predict a continuous target variable from a set of features.

## 📁 Dataset

- `ResearchInformation3.csv`
- You must specify which column is the target (e.g., `"TargetColumn"` in the code).

## ⚙️ Tools Used

- **Python**, **pandas**, **NumPy**
- **Scikit-learn** for model building and evaluation
- **Matplotlib** and **Seaborn** for visualization

## 🧪 Workflow

1. **Load Data**  
   Read the dataset using `pandas`.

2. **Preprocessing**  
   - Handle missing values
   - Select numeric features
   - Split into training and testing sets
   - Standardize features

3. **Model Training**  
   Train a **Random Forest Regressor** with 100 estimators.

4. **Model Evaluation**  
   Evaluate performance using:
   - **Mean Squared Error (MSE)**
   - **R² Score**

5. **Feature Importance**  
   Visualize the top contributing features in prediction.

## 🚀 How to Run

1. Ensure you have Python and the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Update the target column name in the script:
target = df['TargetColumn']
Run the script in Jupyter Notebook or any Python IDE.

📈 Output
Model performance metrics (MSE, R²)

Feature importance bar char
