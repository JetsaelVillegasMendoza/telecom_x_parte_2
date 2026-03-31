# 🤖 Telecom X Part 2 — Customer Churn Prediction

[![Proyecto](https://i.postimg.cc/Jhw2KRyc/una-imagen-estilo-publicitario-para-la-compa-a.jpg)](https://postimg.cc/w1V2j8Q7)
![Status](https://img.shields.io/badge/status-completed-green)

## 📑 Table of Contents
- [🚀 Project Overview](#-project-overview)
- [🎯 Business Problem](#-business-problem)
- [🧠 Approach](#-approach)
- [📊 Key Results](#-key-results)
- [💡 Business Impact](#-business-impact)
- [📂 Repository Contents](#-repository-contents)
- [⚙️ How to Run](#️-how-to-run)
- [🧰 Tech Stack](#-tech-stack)
- [👤 Author](#-author)
- [🏁 Final Note](#-final-note)

## 🚀 Project Overview
Developed a **Machine Learning model to predict customer churn** in a telecom company, identifying high-risk users and key drivers of cancellation.

The project focuses on combining **predictive modeling + business insights** to support data-driven retention strategies.

---

## 🎯 Business Problem
Customer churn represents a critical loss of revenue.  

The goal of this project is to:
- Predict which customers are likely to cancel the service  
- Identify the variables that influence churn  
- Provide actionable insights to improve customer retention  

---

## 🧠 Approach
The project followed a structured data science workflow:

- **Data preparation** using a cleaned dataset from a previous ETL phase  
- **Train-test split (70/30)** ensuring class balance  
- **Model training and comparison**:
  - Decision Tree  
  - Random Forest  
- **Hyperparameter tuning** with `GridSearchCV`  
- **Model evaluation** using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion Matrix  
- **Feature importance analysis** to interpret model decisions  

---

## 📊 Key Results
- The **optimized Random Forest model** achieved the best performance (~79.4% accuracy), outperforming Decision Tree in overall balance.  

- **Top churn drivers identified**:
  - Contract duration (tenure)
  - Total charges  
  - Monthly contract type  
  - Fiber optic service  

- **Key insight**:  
  Customers with **monthly contracts and specific billing patterns** show a higher probability of churn.

---

## 💡 Business Impact
This model enables:
- Early identification of high-risk customers  
- Targeted retention strategies  
- Better allocation of marketing and customer success efforts  

---

## 📂 Repository Contents
- Data preprocessing (from Part 1)  
- Model training and evaluation  
- Performance comparison  
- Visualizations and insights  

Additional project workflow:  
👉 https://trello.com/b/y1FQQnc7/telecomxparte2latam  

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/JetsaelVillegasMendoza/telecom_x_parte_2.git
   ```

2. Navigate to the project folder:
   ```bash
   cd telecom_x_parte_2
   ```

3. Run the notebook using:
   - Jupyter Notebook
   - Google Colab

4. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```

---

## 🧰 Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook / Google Colab  
- Git & GitHub

---

## 👤 Author

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/157757330?v=4" width="115"><br>
  <sub><b>Jetsael Villegas</b></sub>
</p>

---

## 🏁 Final Note

This project was developed as part of the **Oracle Next Education (ONE)** program, in collaboration with **Alura LATAM**, applying core concepts of **Machine Learning**, **model evaluation**, and **data-driven decision-making**.
