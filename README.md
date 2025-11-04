# 🏠Smart Home⚡Energy Consumption Prediction🔮

## 📘 Problem Statement
The objective of this project is to **predict the energy consumption of a smart home** using various environmental and temporal factors such as temperature, humidity, weather conditions, and time-based features (hour, weekday, month, etc.).

This prediction helps optimize energy usage, reduce wastage, and improve energy efficiency in smart homes.

---

## 🧠 Approach
1. **Data Understanding and Preprocessing**
   - The dataset contained both numerical and categorical columns.
   - Categorical columns were encoded appropriately — temporal columns such as hours, weekdays, and months were **kept numeric** to preserve their natural ordering.
   - Missing values were handled, and the dataset was cleaned for modeling.

2. **Feature Engineering**
   - Extracted and encoded temporal features (hour, minute, weekday, month).
   - Encoded categorical variables such as weather conditions using `LabelEncoder`.
   - Normalized numerical data to improve model performance.

3. **Modeling**
   - Applied **Linear Regression**, **Random Forest Regressor**, and **Gradient Boosting Regressor** to compare results.
   - Used **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R² score** for evaluation.

4. **Model Evaluation**
   - Gradient Boosting performed the best among the tested models.
   - Visualized predictions vs. actual consumption for performance assessment.

---

## 🧩 Libraries Used and Their Purpose
| Library | Purpose |
|----------|----------|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical computations |
| `matplotlib`, `seaborn` | Data visualization |
| `sklearn.preprocessing` | Encoding and scaling features |
| `sklearn.model_selection` | Train-test split and cross-validation |
| `sklearn.ensemble` | Machine learning models (Random Forest, Gradient Boosting) |
| `sklearn.metrics` | Model evaluation metrics |

---

## 📊 Results
- **Best Model:** Gradient Boosting Regressor  
- **R² Score:** ~0.89  
- **RMSE:** ~0.12  
- **MAE:** ~0.08  

The model demonstrated strong predictive performance, making it suitable for estimating smart home energy consumption based on temporal and environmental inputs.

---

## ⚙️ How to Run the Code

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/smart-home-energy-prediction.git
cd smart-home-energy-prediction
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
Open Jupyter Notebook or VSCode and run:
```bash
smart_home_energy_regression.ipynb
```

---

## 🧾 Author
**Kanishk Mishra**  
📍 IITM BS Degree in Data Science and Applications  
💻 Passionate about AI, ML, and Data-driven systems

---

## 📜 License
This project is licensed under the **MIT License** — free to use and modify with proper attribution.
