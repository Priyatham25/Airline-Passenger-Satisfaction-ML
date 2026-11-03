# ✈️ Airline Passenger Satisfaction Analysis and Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on analysing and predicting airline passenger satisfaction using Machine Learning algorithms. It uses passenger demographic information, travel details, airline service ratings and flight delay information to identify the factors influencing customer satisfaction.

The main objective is to help airlines understand passenger experiences, identify service-related issues and improve customer satisfaction.

## 🎯 Project Objectives

- Analyse overall airline passenger satisfaction.
- Study satisfaction based on passenger age and travel class.
- Analyse the impact of airline services on passenger satisfaction.
- Examine the relationship between flight delays and customer satisfaction.
- Build and compare different Machine Learning classification models.
- Identify the best-performing model for passenger satisfaction prediction.

## 📊 Dataset Information

- **Total Records:** 103,904
- **Original Features:** 25
- **Target Variable:** Satisfaction
- **Target Categories:** Satisfied and Neutral or Dissatisfied.

The dataset contains passenger information, travel details, service ratings and flight delay information.

## 🛠️ Technologies and Libraries Used

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Scikit-learn** – Machine Learning model development and evaluation.
- **Spyder IDE** – Python development environment.

## 🔍 Data Preprocessing

The following preprocessing techniques were performed:

1. Dataset loading and inspection.
2. Removal of unnecessary columns.
3. Handling missing values using Mean and Mode imputation.
4. Duplicate record checking and removal.
5. Feature engineering using Age Group.
6. One-Hot Encoding for categorical input features.
7. Label Encoding for the target variable.
8. Feature scaling using StandardScaler.
9. Splitting the dataset into 80% training and 20% testing data.

## 🤖 Machine Learning Algorithms

Four supervised Machine Learning algorithms were implemented:

1. **Logistic Regression** – Used for classification based on predicted probabilities.
2. **Decision Tree** – Uses a tree-based structure to classify passenger satisfaction.
3. **Random Forest** – Combines multiple decision trees to improve prediction performance.
4. **Support Vector Machine (SVM)** – Uses a decision boundary to separate different classes.

## 📈 Model Performance

The performance of the four models was evaluated using Accuracy, Precision, Recall and F1-score.

| Machine Learning Model | Accuracy |
|---|---:|
| Logistic Regression | 87.74% |
| Decision Tree | 95.24% |
| Random Forest | 96.15% |
| Support Vector Machine | 87.83% |

**Best Performing Model: Random Forest**

Random Forest achieved the highest accuracy of **96.15%** among the four implemented algorithms.

## 📉 Exploratory Data Analysis (EDA)

The project includes the following visualizations:

- Passenger satisfaction distribution.
- Passenger age distribution.
- Satisfaction based on travel class.
- Satisfaction based on customer type and travel type.
- Correlation heatmap.
- Average airline service ratings.
- Arrival delay analysis.
- Model accuracy comparison.
- Decision Tree visualization.

## 💡 Key Findings

- Business Class passengers show a higher proportion of satisfied passengers.
- Loyal customers generally show higher satisfaction.
- Airline service ratings influence passenger satisfaction.
- Departure delay and arrival delay have a strong positive correlation.
- Random Forest achieved the highest classification accuracy.

## 🏁 Conclusion

This project demonstrates how Machine Learning can be used to analyse and predict airline passenger satisfaction. Among the four implemented classification algorithms, Random Forest delivered the best performance with 96.15% accuracy.

The findings can help airlines understand passenger expectations, improve service quality and enhance the overall customer experience.

## 🚀 Future Enhancements

- Apply hyperparameter tuning to improve model performance.
- Use cross-validation for more reliable evaluation.
- Include additional external factors such as weather conditions.
- Develop a web application for real-time passenger satisfaction prediction.
- Explore additional Machine Learning algorithms.

## 👨‍💻 Author

**Lanka Priyatham Raj**

B.Tech – Data Science  
Lovely Professional University

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
