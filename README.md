# CO2 Emission Analysis using Machine Learning

A machine learning project that analyzes and predicts **CO₂ emissions** using different regression algorithms.
The project compares the performance of **Linear Regression**, **Decision Tree**, and **Random Forest** models to determine the most accurate approach for CO₂ emission prediction.

---

## 📌 Project Overview

The rise in carbon dioxide (CO₂) emissions is a major environmental challenge worldwide.
This project uses machine learning techniques to analyze relationships between vehicle parameters and CO₂ emissions and predicts emission levels using multiple ML models.

The project also includes a simple **web-based visualization dashboard** built using **HTML, CSS, and JavaScript** for displaying graphs and model comparison results.

---

## 🎯 Objectives

* Analyze the relationship between vehicle features and CO₂ emissions
* Implement multiple machine learning algorithms
* Compare models using evaluation metrics
* Identify the best-performing model for prediction

---

## 🛠 Technologies Used

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Pickle

### Frontend

* HTML
* CSS
* JavaScript

---

## 📂 Dataset Used

### 1. Fuel Consumption Dataset

Used for training machine learning models to predict CO₂ emissions.

### 2. CO₂ Sector Dataset

Used for sector-wise and yearly CO₂ emission analysis.

Dataset Sources:

* [CO₂ Emissions Dataset](https://www.kaggle.com/datasets/saloni1712/co2-emissions?utm_source=chatgpt.com)
* [Fuel Consumption Dataset](https://www.kaggle.com/datasets/ahmettyilmazz/fuel-consumption?utm_source=chatgpt.com)

---

## ⚙️ Machine Learning Models Implemented

### 1. Linear Regression

* Simple regression model
* Performs well on linear relationships
* Higher prediction error for complex datasets

### 2. Decision Tree Regressor

* Captures non-linear patterns
* Can overfit on training data

### 3. Random Forest Regressor

* Ensemble learning algorithm
* Combines multiple decision trees
* Produces the best overall accuracy

---

## 📊 Model Performance

| Algorithm         | MSE    | RMSE  | R² Score |
| ----------------- | ------ | ----- | -------- |
| Linear Regression | 410.68 | 20.27 | 0.883    |
| Decision Tree     | 158.64 | 12.60 | 0.955    |
| Random Forest     | 155.00 | 12.45 | 0.956    |

### ✅ Best Model

**Random Forest Regressor** achieved the best performance with:

* Lowest prediction error
* Highest R² score
* Better balance between bias and variance

---

## 📈 Features of the Project

* CO₂ emission prediction using ML
* Model comparison visualization
* Sector-wise emission analysis
* Year-wise emission trends
* Interactive frontend dashboard

---

## 📷 Project Output

The web dashboard displays:

* Overall CO₂ emission graphs
* Model prediction graphs
* Model comparison charts
* Algorithm performance table

---

## 📁 Project Structure

```bash
CO2-Emission-Analysis/
│
├── FuelConsumption.csv
├── dataset.csv
├── model.pkl
├── co2_analysis.ipynb
│
├── index.html
├── style.css
├── script.js
│
├── co2_graph.png
├── lr_graph.png
├── dt_graph.png
├── rf_graph.png
├── model_comparision_graph.png
│
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-github-repo-link>
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the `.ipynb` file and execute all cells.

### 4. Run Frontend

Open `index.html` in a browser.

---

## 📌 Future Improvements

* Add deep learning models
* Deploy using Flask or Streamlit
* Real-time CO₂ prediction
* Add more environmental datasets
* Improve UI/UX dashboard design

---

## 📚 References

* [Scikit-learn Documentation](https://scikit-learn.org/stable/?utm_source=chatgpt.com)
* [Pandas Documentation](https://pandas.pydata.org/docs/?utm_source=chatgpt.com)
* [Matplotlib Documentation](https://matplotlib.org/stable/contents.html?utm_source=chatgpt.com)

---

## 👩‍💻 Author

**Avilipsa Mahapatra**  
School of Computer Engineering  
KIIT - DU
