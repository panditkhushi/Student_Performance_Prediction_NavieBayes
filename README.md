
## 👩‍💻 Author
**Khushi Pandit**

# 🎓 Student Performance Prediction Using Naive Bayes

## 📌 Project Overview
This project predicts whether a student will **Pass or Fail** based on their academic scores using the **Naive Bayes classification algorithm**.  
The model is trained on a real-world dataset from **Kaggle (Students Performance in Exams)** and uses **Multinomial Naive Bayes** after appropriate data preprocessing.


## 🎯 Objective
- To analyze student exam performance
- To classify students into **Pass / Fail**
- To implement **Multinomial Naive Bayes** for educational data
- To evaluate the model using standard classification metrics


## 📂 Dataset Information
- **Dataset Name:** Students Performance in Exams  
- **Source:** Kaggle  
- **File:** `StudentsPerformance.csv`

### 📊 Features Used
| Feature Name | Description |
|-------------|------------|
| math score | Mathematics exam score |
| reading score | Reading exam score |
| writing score | Writing exam score |

### 🎯 Target Variable
- **result**
  - `1` → Pass (Average score ≥ 50)
  - `0` → Fail (Average score < 50)

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn  


## 🧠 Machine Learning Model
### 🔹 Multinomial Naive Bayes
- Suitable for **discrete/count-based data**
- Requires **feature discretization**
- Fast and efficient for classification tasks

## 🔄 Project Workflow
1. Load the dataset
2. Calculate average score
3. Create target variable (Pass/Fail)
4. Discretize numerical features
5. Split data into training and testing sets
6. Train Multinomial Naive Bayes model
7. Evaluate model performance
8. Predict result for new student data


## 📊 Model Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score


## 📌 Example Prediction
The model can predict whether a new student will **Pass or Fail** based on their:
- Math score
- Reading score
- Writing score


## ✅ Advantages
- Simple and fast algorithm
- Works well with categorical/discretized data
- Easy to interpret and explain


## ❌ Limitations
- Assumes feature independence
- Performance depends on proper data preprocessing
- Not ideal for highly correlated features


## 🔮 Future Enhancements
- Compare with Gaussian and Bernoulli Naive Bayes
- Add data visualization
- Deploy as a web app using Streamlit or Flask
- Extend to multi-class prediction (Excellent / Good / Average / Fail)

## 📎 Conclusion
This project demonstrates how Naive Bayes can be effectively used in the education domain to predict student performance.  
It provides a simple yet powerful approach for academic analysis and early intervention systems.


