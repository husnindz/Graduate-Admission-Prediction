# 🎓 Graduate Admission Prediction using Machine Learning

This project aims to predict the probability of graduate admission using machine learning regression techniques based on applicant academic and profile data.

The analysis follows a structured pipeline consisting of six main stages, from data understanding to model evaluation, to ensure a comprehensive and data-driven approach.

---

## 📊 Dataset

- Source: [Graduate Admissions Dataset](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)
- Type: Tabular data
- Target: Chance of Admit
- Features:
  - GRE Scores
  - TOEFL Scores 
  - University Rating 
  - Statement of Purpose and Letter of Recommendation Strength 
  - Undergraduate GPA 
  - Research Experience 
  - Chance of Admit
---

## ⚙️ Project Workflow

### 1. Data Understanding
- Load dataset and inspect structure (head, tail, shape)
- Analyze data types and descriptive statistics
- Check missing values and data consistency

### 2. Exploratory Data Analysis (EDA)
- Visualize missing values using heatmap
- Analyze feature distributions using histograms
- Explore relationships using pairplot and scatter plots
- Identify feature correlations using correlation matrix

### 3. Data Preprocessing
- Separate features (X) and target variable (y)
- Convert data into NumPy arrays
- Reshape target variable for modeling
- Split dataset into training and testing sets

### 4. Modeling
- Train regression model using **XGBoost Regressor**
- Initial model configuration:
  - learning_rate = 0.1
  - max_depth = 2
  - n_estimators = 100

### 5. Evaluation
- Evaluate model using multiple metrics:
  - R² Score
  - RMSE
  - MSE
  - MAE
- Compare predicted vs actual values

### 6. Hyperparameter Tuning
- Apply **GridSearchCV** to optimize model performance
- Tune parameters:
  - n_estimators
  - max_depth
  - learning_rate
  - subsample
- Use cross-validation (cv=5) for robust evaluation
- Select best model based on R² score

---

## 🧠 Key Concept

This project demonstrates:
- End-to-end **Machine Learning pipeline**
- **Regression modeling with XGBoost**
- **Hyperparameter tuning using GridSearchCV**
- **Model evaluation with multiple metrics**

---

## 📈 Results

- Successfully built a predictive model for admission probability
- Performance improved after hyperparameter tuning
- XGBoost effectively captured relationships between academic features and admission chances

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn
- Joblib

---

## 📌 Future Improvements

- Evaluate model performance using additional datasets
- Compare with other models (Linear Regression, Random Forest, etc.)
- Deploy model into a simple web application
- Add explainability (SHAP / feature importance)
  
---

## 👤 Author

- GitHub: [husnindz](https://github.com/husnindz)
