```markdown
# 🧠 MNIST Digit Recognition Web App

A professional web application to classify handwritten digits (0–9) from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), using machine learning models with `GridSearchCV` for optimal performance. The app is built with **Streamlit** and deployed for real-time usage.

## 🚀 Live Demo

👉 [Click to Open the Web App](https://talhadeveloperr-mnist-digit-recog-streamlit-appapp-6wg1ti.streamlit.app/)
```
---

## 📌 Project Features

- 📦 Cleaned and preprocessed MNIST dataset
- 🧹 Feature scaling and reshaping
- 🔍 Hyperparameter tuning using `GridSearchCV`
- 🧠 Models used:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors
- 💯 Accuracy and classification report for each model
- 💾 Model saved with `joblib`
- 🌐 Streamlit frontend for user digit drawing and prediction



## 🛠️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/mnist-digit-recognition.git
cd mnist-digit-recognition
````

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run streamlit_app.py
```

---

## 📊 Model Accuracy

| Model               | Accuracy (after GridSearchCV) |
| ------------------- | ----------------------------- |
| Logistic Regression | \~92%                         |
| SVM                 | \~94%                         |
| Random Forest       | \~96%                         |
| KNN                 | \~93%                         |

---

## 🧠 Sample Predictions

Users can draw digits on a canvas, and the app will recognize and classify the digit in real-time.

---

## 📌 Tech Stack

* Python
* Streamlit
* Scikit-learn
* NumPy, Pandas, Matplotlib
* GridSearchCV
* Joblib



