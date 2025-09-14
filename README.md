# Student Placement Prediction

## 📌 Problem Statement
The objective of this project is to analyze student data and build a predictive model to determine whether a student will be placed or not.  
Given various academic and personal attributes of students, we aim to identify the key factors affecting placements and provide useful insights for career guidance.

## 📊 Dataset
The dataset used is `student placement data.csv`.  
It contains information about students such as:
- Academic scores (e.g., 10th %, 12th %, CGPA)
- Demographics (e.g., gender, specialization)
- Work experience
- Placement status (Placed / Not Placed)

## 🚀 Approach
1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features
   - Normalize/scale numerical features

2. **Exploratory Data Analysis (EDA)**
   - Distribution of placement status
   - Correlation between features
   - Key insights about placed vs non-placed students

3. **Model Building**
   - Split data into train and test sets
   - Train classification models (e.g., Logistic Regression, Decision Tree, Random Forest, etc.)
   - Evaluate model performance using accuracy, precision, recall, F1-score

4. **Results**
   - Identify most important features influencing placement
   - Provide accuracy score and evaluation metrics

## 📈 Results / Insights
- Higher academic scores generally increase placement chances
- Work experience positively affects placement probability
- Some specializations may have higher placement rates

## ⚙️ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/Keshavraj52/EDA_PRACTICE.git
   cd student-placement-prediction
