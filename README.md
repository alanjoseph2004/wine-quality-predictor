# 🍷 Wine Quality Predictor

A simple and interactive machine learning web application that predicts the quality of wine based on various physicochemical features from the UCI Wine Quality dataset.

---

## 🚀 Live Demo

🔗 [Access the App on Render](https://wine-quality-predictor-uafv.onrender.com)

---

## 📌 Features

- Predicts wine quality based on input chemical attributes
- Built with Scikit-learn classification models
- User-friendly frontend using Streamlit
- Hosted on Render for easy access
- Real-time results with minimal latency

---

## 🧠 Dataset

- **Source**: [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- Contains 11 physicochemical features like:
  - Fixed Acidity
  - Volatile Acidity
  - Citric Acid
  - Residual Sugar
  - Chlorides
  - Free Sulfur Dioxide
  - Total Sulfur Dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol
- Target: Wine quality (score between 0–10)

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend / ML**: Scikit-learn, Pandas, NumPy, Matplotlib
- **Deployment**: Render

---

## 🧪 Model

- Preprocessing: StandardScaler, Label Encoding (if needed)
- Models Tried: Logistic Regression, Random Forest, Gradient Boosting
- Best Performing Model: `RandomForestClassifier`
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score

---

## 🧑‍💻 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/wine-quality-predictor.git
cd wine-quality-predictor

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
