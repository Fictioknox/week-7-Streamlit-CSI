# 🌸 Iris Flower Classifier Web App

This project is a **Streamlit web application** that deploys a trained **Logistic Regression machine learning model** to classify Iris flowers based on user input. The app allows users to input measurements of a flower's features and receive real-time predictions along with visual explanations of model performance.

---

## 🎯 Project Objectives

- ✅ Deploy a trained machine learning model using **Streamlit**
- ✅ Allow users to **interactively input data**
- ✅ Provide **real-time predictions**
- ✅ Help users understand model behavior via **visualizations**


## 🛠️ Features

- 🌿 **User Input Interface** (via sidebar sliders)
- 🔍 **Real-time Prediction** using Logistic Regression
- 📊 **Prediction Probabilities** displayed in table format
- 📉 **Confusion Matrix** for model evaluation
- ☁️ **Deployed on Streamlit Cloud** – No local installation needed

---

## 🚀 Try It Live

👉 [Click here to launch the app](https://week-7-app-csi-wyrkhvdmdgfep6ygtq2i8k.streamlit.app/)

---

## 🧪 How the Model Works

- Dataset: [Iris flower dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Model: `LogisticRegression` from `scikit-learn`
- Training: 80% train / 20% test split
- Evaluation: Confusion matrix on test set

---

## 📦 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/iris-streamlit-app.git
cd iris-streamlit-app

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Streamlit app
streamlit run app.py
