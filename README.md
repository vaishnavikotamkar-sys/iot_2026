# 🌳 Decision Tree Based Student Performance Prediction Model

> A Machine Learning project developed using a Decision Tree Regression model to predict student exam performance based on academic and personal factors.
---

# 👨‍💻 Developer Information

**Student Name:** Tanushree Kotamkar

**Roll Number:** 119

**College:** Priyadarshani College Of Engineering,Nagpur

**Department:** Industrial Internet Of Things

**Academic Year:** 2025–2026

---

# 📌 Project Overview

This project demonstrates the implementation of a Decision Tree Regression model using Python and Jupyter Notebook. The primary objective is to build a machine learning model that can predict student exam performance by analyzing various academic and personal factors.

The project follows the complete machine learning pipeline, including data loading, data preprocessing, exploratory data analysis, feature encoding, model building, training, evaluation, and prediction.

The implementation focuses on understanding how Decision Tree algorithms can be used to analyze structured datasets and solve real-world prediction problems.
---
# 🎯 Project Objectives

- Understand the Decision Tree algorithm.
- Implement a Decision Tree Regression model using Python.
- Perform data preprocessing and feature encoding.
- Analyze student performance factors using exploratory data analysis.
- Train the Decision Tree model on the dataset.
- Evaluate model performance using MAE, MSE, and R² Score.
- Generate predictions using the trained model.
- Demonstrate an end-to-end machine learning workflow.

---
# 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---
# 🏗 Project Architecture
            Dataset
               │
               ▼
      Data Collection
               │
               ▼
    Data Preprocessing
               │
               ▼
    Feature Encoding
               │
               ▼
      Train/Test Split
               │
               ▼
    Decision Tree Model
    ┌─────────────────────┐
    │  Root Node          │
    │  Decision Rules     │
    │  Branches           │
    │  Leaf Nodes         │
    └─────────────────────┘
               │
               ▼
       Model Training
               │
               ▼
      Model Evaluation
               │
               ▼
      Feature Importance
               │
               ▼
        Final Prediction
```

---

# 🔄 Project Workflow

### Step 1 – Data Collection

The Student Performance Factors dataset is loaded into the notebook for analysis and model development.

↓

### Step 2 – Data Cleaning

- Check missing values
- Handle incomplete data
- Prepare the dataset for further processing

↓

### Step 3 – Data Preprocessing

- Encode categorical variables into numerical format
- Analyze dataset features
- Prepare data for machine learning

↓

### Step 4 – Exploratory Data Analysis (EDA)

- Analyze feature relationships
- Visualize data using graphs
- Identify important factors affecting student performance

↓

### Step 5 – Dataset Splitting

The dataset is divided into:

- Training Dataset
- Testing Dataset

↓

### Step 6 – Decision Tree Model Creation

A Decision Tree Regression model is created using:

- Root Node
- Decision Rules
- Branches
- Leaf Nodes

The model learns patterns from input features to predict exam scores.

↓

### Step 7 – Model Training

The Decision Tree model is trained using the training dataset to learn relationships between features and target values.

↓

### Step 8 – Model Evaluation

Model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

↓

### Step 9 – Prediction

The trained Decision Tree model predicts exam scores for unseen student data.

---

Student-Performance-Decision-Tree
│
├── Student_Performance_Decision_Tree.ipynb
├── README.md
├── StudentPerformanceFactors.csv
├── outputs/
│ ├── feature_importance.png
│ └── actual_vs_predicted.png
├── models/
│ └── student_performance_decision_tree.pkl
└── requirements.txt

---

# 🧠 ANN Architecture

```
                     Input Features
                │
                ▼
          Root Node
                │
                ▼
      Decision Rules / Conditions
                │
      ┌─────────┴─────────┐
      ▼                   ▼
   Branch 1            Branch 2
      │                   │
      ▼                   ▼
          Leaf Nodes
                │
                ▼
          Exam Score
          Prediction
---
          
# ⚙ Key Features

- Data preprocessing
- Categorical feature encoding
- Exploratory Data Analysis (EDA)
- Decision Tree Regression implementation
- Model training
- Exam score prediction
- Performance evaluation using MAE, MSE, and R² Score
- Feature importance analysis
- Data visualization
- Complete Machine Learning workflow

---
# 💡 Key Skills Demonstrated

- Python Programming
- Machine Learning
- Decision Tree Algorithm
- Data Analysis
- Data Preprocessing
- Feature Encoding
- Exploratory Data Analysis (EDA)
- Feature Importance Analysis
- Data Visualization
- Model Evaluation
- Problem Solving

---
# 📊 Expected Outputs

- Cleaned and preprocessed dataset
- Trained Decision Tree model
- Student exam score prediction results
- Model performance evaluation (MAE, MSE, R² Score)
- Feature importance analysis
- Data visualization graphs
- Decision Tree structure visualization

---

# 📈 Future Improvements

- Apply hyperparameter tuning to improve Decision Tree performance
- Use a larger and more diverse student performance dataset
- Perform advanced feature engineering
- Compare with other machine learning algorithms like Random Forest and Gradient Boosting
- Improve model accuracy and prediction performance
- Deploy the trained model using Flask or FastAPI
- Create an interactive web application for student performance prediction
---

# 📚 Learning Outcomes

Through this project, the following concepts were explored:

- Machine Learning fundamentals
- Decision Tree Regression algorithm
- Data preprocessing and feature encoding
- Exploratory Data Analysis (EDA)
- Feature importance analysis
- Model training and prediction
- Model evaluation techniques using MAE, MSE, and R² Score
- Complete Machine Learning workflow

---
# 📖 References

- Scikit-learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation
- Machine Learning and Decision Tree algorithm resources


---

# 📄 License

This project is created for academic and educational purposes.

---

# 🙏 Acknowledgement

I sincerely thank my faculty members, department, and college for providing guidance and support throughout the development of this project. This work helped me gain practical knowledge of Artificial Neural Networks and Machine Learning.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
