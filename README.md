# Alzheimer Prediction with Decision Trees

This repository contains a supervised machine learning project focused on predicting Alzheimer's diagnosis using a **Decision Tree** model. The goal is to analyze the model's performance based on evaluation metrics such as accuracy, precision, recall, and F1-score, while exploring the impact of data distribution on the model's effectiveness.

---

## 📋 About the Project

Diagnosing Alzheimer's is a complex challenge due to the influence of various factors like genetics, lifestyle, and environment. This project uses a dataset containing information such as age, BMI, education level, sleep quality, air pollution exposure, and more to predict the presence or absence of Alzheimer's.

The Decision Tree model was chosen for its ability to handle both categorical and numerical data, as well as its interpretability. The project includes:
- Data preprocessing (encoding categorical variables).
- Model training and evaluation.
- Detailed analysis of performance metrics.
- Visualization of the generated decision tree.

---

## 📊 Performance Metrics

The model was evaluated based on the following metrics:
- **Accuracy**: 72.58%
- **Precision**: 64.67%
- **Recall**: 74.35%
- **F1-Score**: 69.07%

The confusion matrix revealed:
- **9320 True Negatives (TN)**
- **3745 False Positives (FP)**
- **2365 False Negatives (FN)**
- **6855 True Positives (TP)**

---

## 🧠 Final Considerations

The model showed good overall performance, but there is room for improvement, especially in reducing false positives and false negatives. The imbalanced data distribution (more "No" cases than "Yes") may be influencing the model's performance. Future work could explore data balancing techniques and other machine learning algorithms to improve precision and recall.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** for data manipulation.
- **Scikit-learn** for implementing the Decision Tree model and evaluation metrics.
- **Matplotlib** for visualizing the decision tree.

---

## 📂 Repository Structure

- **`alzheimers_prediction_dataset.csv`**: Dataset used in the project.
- **`notebook_analysis.ipynb`**: Notebook containing the complete analysis, from preprocessing to model evaluation.
- **`README.md`**: This file, with information about the project.

---

## 👥 Authors

- **Renato Dias Ferreira Campos** - 

---

Feel free to explore the code, suggest improvements, or contribute to the project! �
