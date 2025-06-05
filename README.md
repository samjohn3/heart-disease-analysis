# 🫀 Heart Disease Analysis Using Python

This project involves exploratory data analysis (EDA) on a healthcare dataset to understand the patterns and factors contributing to heart disease. Visualizations and descriptive statistics were used to derive insights.

---

## 📁 Dataset

- Source: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- Description: The dataset contains medical attributes such as age, sex, chest pain type, cholesterol, blood pressure, maximum heart rate, and heart disease status.

---

## 🔍 Exploratory Data Analysis

The following visualizations and analyses were performed:

- 📊 **Summary Statistics** of all numeric features  
- 🧍‍♂️ **Gender vs Heart Disease** comparison  
- 📈 **Age Distribution** of patients  
- 💔 **Chest Pain Type vs Heart Disease**  
- 💉 **Resting Blood Pressure & Cholesterol** Distribution  
- ❤️‍🔥 **Max Heart Rate vs Heart Disease**  
- 📉 **Oldpeak (ST Depression)** Distribution  
- 🔥 **Correlation Heatmap** to find relationships among features

---

## 🧠 Key Insights

- **Asymptomatic chest pain (cp=3)** showed a higher link to heart disease.
- **Exercise-induced angina** was more prevalent among patients with heart disease.
- **Max heart rate (thalach)** was generally lower in those with heart disease.
- The **correlation heatmap** revealed useful relationships, such as negative correlation between `thalach` and `target`.

---

## 🛠 Tools Used

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- Jupyter Notebook

---

## 📌 Project Structure


---

## 📈 Future Improvements

- Apply ML models to predict heart disease (e.g. Logistic Regression, Random Forest).
- Perform advanced feature engineering or outlier detection.
- Deploy insights as a dashboard using Streamlit or Flask.

---

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- UCI Machine Learning Repository
- Kaggle contributors for dataset access

