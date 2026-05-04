# BigMart Sales Prediction

## 📌 Project Overview

This project predicts sales of products across different BigMart outlets using machine learning techniques.

## 📊 Dataset

The dataset contains information about products and outlets, including:

* Item Weight
* Item Fat Content
* Item Visibility
* Item Type
* Item MRP
* Outlet details

## ⚙️ Steps Performed

* Data Cleaning (handling missing values)
* Feature Engineering
* Encoding categorical variables
* Model Training & Evaluation

## 🤖 Models Used

* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

## 📈 Results

| Model             | RMSE  | R²    |
| ----------------- | ----- | ----- |
| Random Forest     | ~1034 | ~0.60 |
| Gradient Boosting | ~1048 | ~0.59 |
| XGBoost           | ~1060 | -     |

## 🚀 How to Run

```bash
git clone https://github.com/your-username/bigmart-sales-prediction.git
cd bigmart-sales-prediction
pip install -r requirements.txt
```

Run the notebook or scripts.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost

## 📌 Future Improvements

* Hyperparameter tuning
* Feature selection
* Deployment using Flask/Streamlit

## 📜 License

This project is licensed under the MIT License.
