# student-performance-analysis
An Data Visualization project analyzing how student habits affect academic performance.

Student Performance Prediction Model

This project contains a machine learning model for predicting student academic performance based on their daily habits. The model uses data analysis and machine learning techniques to understand how lifestyle factors like study time, sleep, and physical activity influence academic outcomes.

Features

Data Preprocessing: Cleans the dataset by removing unnecessary columns, handling missing values, and detecting outliers.

Exploratory Data Analysis (EDA): Provides statistical summaries and visualizations to identify trends, correlations, and anomalies in student habits.

Modeling: Trains using machine learning algorithms like Linear Regression, Random Forest, and Gradient Boosting to predict academic scores.

Evaluation: Assesses model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

Technologies Used

Python: Main programming language.

Pandas & NumPy: For data manipulation and numerical computations.

Scikit-learn: For training and evaluating machine learning models.

Matplotlib & Seaborn: For creating visualizations and plots during EDA.

Jupyter Notebook: For organizing analysis and visual storytelling.

Instructions

Clone the repository:
git clone https://github.com/aryansahu0325/student-performance-prediction.git

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook notebooks/EDA.ipynb

Train and evaluate model:
python src/train_model.py
python src/evaluate_model.py

Dataset

The dataset includes the following features:

Study_Hours_Per_Day

Sleep_Hours_Per_Day

Screen_Time_Per_Day

Physical_Activity_Hours

Attendance_Percentage

Healthy_Eating_Score

Academic_Performance (Target Variable)

Each record represents a student's self-reported habits and their academic performance score.

Folder Structure

student-performance-prediction/
├── data/ → Dataset file
├── notebooks/ → Jupyter notebooks (EDA, modeling)
├── src/ → Python scripts (preprocessing, training, evaluation)
├── models/ → Saved model files
├── requirements.txt → Project dependencies
└── README.md → Project description

Credits

Developed as part of a data analysis project focused on educational performance prediction using real-world behavioral data.
