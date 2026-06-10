CodeAlpha Disease Prediction Project
🩺 Disease Prediction using Machine Learning

A Machine Learning project developed as part of the CodeAlpha Machine Learning Internship.

This project predicts whether a person is diabetic or non-diabetic using medical data and classification algorithms such as Logistic Regression and Random Forest.

📌 Project Overview

The goal of this project is to build a predictive machine learning model capable of analyzing patient medical data and predicting the possibility of diabetes.

The project demonstrates the complete Machine Learning workflow:

Data Collection
Data Preprocessing
Feature & Target Separation
Train-Test Splitting
Model Training
Model Evaluation
Prediction System
Accuracy Comparison


🚀 Technologies Used
Python
NumPy
Pandas
Scikit-learn
Jupyter Notebook
VS Code


📂 Dataset Used

Dataset: Diabetes Dataset

Features include:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age

Target Variable:

Outcome
0 → Non-Diabetic
1 → Diabetic
🧠 Machine Learning Algorithms Used

1. Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems.

Accuracy Achieved:
Training Accuracy: ~78%
Testing Accuracy: ~75%

2. Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

Accuracy Achieved:
Testing Accuracy: ~75%
⚙️ Installation & Setup
Step 1: Clone Repository
git clone https://github.com/yourusername/CodeAlpha_Disease_Prediction.git

Step 2: Navigate to Project Folder
cd CodeAlpha_DiseasePrediction

Step 3: Install Dependencies
pip install -r requirements.txt
Step 4: Run Jupyter Notebook
jupyter notebook


📊 Project Workflow


1. Import Libraries

Libraries such as Pandas, NumPy, and Scikit-learn were imported for data analysis and machine learning.

2. Load Dataset

The diabetes dataset was loaded using Pandas.

3. Data Preprocessing
Checked dataset structure
Separated features and target variable
Prepared data for model training


4. Train-Test Split

Dataset was split into:

80% Training Data
20% Testing Data


5. Model Training

Models were trained using:

Logistic Regression
Random Forest Classifier


6. Model Evaluation

Accuracy score was used to evaluate model performance.


7. Prediction System

A prediction system was created to test custom patient data.

🧪 Sample Prediction
input_data = (6,148,72,35,0,33.6,0.627,50)
Prediction Result:
The person is diabetic


📈 Future Improvements
Build a Streamlit Web App
Improve model accuracy using feature scaling
Add more medical datasets
Deploy project online
Add real-time user input interface


📸 Project Output

This project successfully predicts whether a person is diabetic or non-diabetic based on medical information.

🏆 Internship Task

This project was completed as part of the:
CodeAlpha Machine Learning Internship


👨‍💻 Author

Vivek Vipparla