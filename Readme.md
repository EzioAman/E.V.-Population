# ⚡ Electric Vehicle Range Prediction (Machine Learning)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A machine learning project that predicts the **electric driving range of electric vehicles (EVs)** using vehicle characteristics such as model year, vehicle type, manufacturer, and price.

The project demonstrates a **complete ML pipeline including data preprocessing, feature engineering, model training, evaluation, and model interpretability.**

---

# 📊 Project Overview

Electric vehicles vary significantly in driving range depending on **technology improvements, manufacturer design, and vehicle type**.

This project builds a **Random Forest regression model** to predict EV range based on key vehicle attributes.

The model also analyzes **feature importance** to determine which factors most influence EV performance.

---

# 🧠 Machine Learning Workflow

The project follows a standard ML pipeline:

1. Data Cleaning
2. Feature Engineering
3. Categorical Encoding
4. Train/Test Split
5. Model Training
6. Model Evaluation
7. Model Interpretability

---

# 📁 Dataset Features

The dataset contains information about electric vehicles including:

| Feature               | Description                         |
| --------------------- | ----------------------------------- |
| Model Year            | Manufacturing year of the vehicle   |
| Electric Vehicle Type | BEV or Plug-in Hybrid               |
| Make                  | Manufacturer (Tesla, Nissan, etc.)  |
| Base MSRP             | Manufacturer suggested retail price |
| Electric Range        | Driving range on electric power     |

**Target Variable**

```
Electric Range
```

---

# ⚙️ Model Used

### Random Forest Regressor

Random Forest was chosen because it:

* Handles **non-linear relationships**
* Works well on **tabular datasets**
* Provides **feature importance for interpretability**

Model configuration:

```python
RandomForestRegressor(
    n_estimators=200,
    random_state=42
)
```

---

# 📈 Model Performance

Evaluation metrics used:

| Metric   | Value    |
| -------- | -------- |
| RMSE     | ~7 miles |
| R² Score | ~0.99    |

The model explains **~99% of the variance in EV range**, indicating strong predictive performance on the dataset.

---

# 🔍 Feature Importance

The model highlights which variables most influence EV range.

Top contributors include:

* **Model Year**
* **Electric Vehicle Type**
* **Manufacturer**

This shows that **technological advancements and vehicle design play a major role in EV driving range.**

---

# 📊 Feature Importance Visualization

The project includes a visualization of the top features influencing electric vehicle range.

This helps interpret how the machine learning model makes predictions.

---

# 🛠 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-Learn**
* **Matplotlib**
* **Jupyter Notebook**

---

# 📂 Project Structure

```
Electric-Vehicle-Range-Prediction
│
├── Electric Vehicle Population.ipynb
├── dataset.csv
├── README.md
```

---

# 🚀 Running the Project

Clone the repository:

```
git clone https://github.com/EzioAman/electric-vehicle-range-prediction.git
```

Install dependencies:

```
pip install pandas numpy scikit-learn matplotlib
```

Run Jupyter Notebook:

```
jupyter notebook
```

Open the notebook and run all cells.

---

# 📌 Key Takeaways

✔ Built a full machine learning pipeline
✔ Applied categorical encoding for vehicle features
✔ Trained a Random Forest regression model
✔ Evaluated model performance using RMSE and R²
✔ Interpreted results using feature importance

---

# 👤 Author

**Aman Sinha**

GitHub: https://github.com/EzioAman
