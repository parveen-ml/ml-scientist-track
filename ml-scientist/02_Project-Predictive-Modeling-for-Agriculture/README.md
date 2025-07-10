# 🌾 Predictive Modeling for Agriculture

This project helps farmers identify the **most important soil feature** for predicting the best crop to plant, using **machine learning models** and **feature selection techniques**.

> 🧠 A single feature from among Nitrogen (N), Phosphorous (P), Potassium (K), and pH is to be chosen — based on its predictive power for classifying crop types.

---

## 📁 Dataset

The dataset (`soil_measures.csv`) contains:

- `N`: Nitrogen content ratio in the soil
- `P`: Phosphorous content ratio
- `K`: Potassium content ratio
- `ph`: pH value of the soil
- `crop`: Optimal crop for the given soil metrics (target variable)

---

## 🧪 Project Objectives

- Perform **exploratory data analysis (EDA)** to understand soil and crop distributions
- Evaluate **F1 score performance** of logistic regression models using one feature at a time
- Identify and visualize the **best predictive feature**
- Optionally use **Random Forest** to compare feature importances


## 🧠 Machine Learning Models Used

- **Logistic Regression (Multiclass)** — tested individually with each feature
- **Random Forest Classifier** — for full model + feature importance

---

## 🏆 Results

- ✅ **Best Predictive Feature:** `K` (Potassium content)
- 🏁 **F1 Score** with `K` only: ~0.235 (Weighted)
- 🌿 Potassium showed the strongest individual predictive power for classifying crop types

---

## 🛠️ Tools & Libraries

- Python 3.11+
- `pandas`, `scikit-learn`, `seaborn`, `matplotlib`

---

## 🚀 How to Run

1. Clone the repo
2. Place the dataset `soil_measures.csv` in the root folder
3. Run `predictive_modeling.ipynb` in Jupyter or VS Code
4. Plots will automatically display or can be saved to `/images` folder

---

## 🤝 License

This project is for educational purposes (DataCamp project extension).  
Feel free to fork and modify it.

---

## 📌 Author

**Parveen Kashyap**  
Aspiring AI/ML Developer | [LinkedIn](https://www.linkedin.com/in/parveen-kashyap44/)
