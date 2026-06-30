# spam-classifier-ml
# 📩 SMS Spam Classifier

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using **TF-IDF Vectorization** and **Scikit-learn**.

---
## 🚀 Project Overview

This project demonstrates an end-to-end Machine Learning pipeline for SMS spam detection. It processes text messages, converts them into numerical features using TF-IDF, trains a machine learning model, and predicts whether a given message is **Spam** or **Ham**.
---

## ✨ Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Text Vectorization using TF-IDF
- Model Training using Multinomial Naive Bayes
- Model Evaluation
- Spam Prediction on Custom Messages
- Model Saving using Joblib

---
## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---
## 📂 Dataset

**Dataset:** SMS Spam Collection Dataset

The dataset contains **5,572 SMS messages** labeled as:

- **Ham** – Legitimate messages
- **Spam** – Unwanted promotional or fraudulent messages

Dataset Source:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

---
## 🔄 Machine Learning Pipeline

1. Load the Dataset
2. Clean the Data
3. Perform Exploratory Data Analysis (EDA)
4. Split the Dataset into Training and Testing Sets
5. Convert Text into Numerical Features using TF-IDF
6. Train the Machine Learning Model
7. Evaluate Model Performance
8. Predict Custom Messages
9. Save the Trained Model

---
## 🤖 Machine Learning Model

**Primary Model**
- Multinomial Naive Bayes

**Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---
## 📈 Results

**Model Accuracy:** **95.55%**

The model performs well on the SMS Spam Collection dataset and correctly classifies the majority of spam and ham messages.

---
## 💻 Sample Prediction

**Input:**

Congratulations! You have won a free prize. Click here to claim now!

**Prediction:**
Spam

---
**Input:**

Hey, are you coming to college today?

**Prediction:**
Ham

---
## 📁 Project Structure

```
sms-spam-classifier/
│
├── Spam_Classifier.ipynb
├── spam_model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

---
## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sms-spam-classifier.git
```

### 2. Navigate to the Project Folder

```bash
cd sms-spam-classifier
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Open `Spam_Classifier.ipynb` using Jupyter Notebook or Google Colab.

---
## 📌 Future Improvements

- Build a Streamlit Web Application
- Compare Multiple Machine Learning Models
- Perform Hyperparameter Tuning
- Deploy the Application Online
- Experiment with Transformer Models (BERT)

---
## 👩‍💻 Author
**Harshitha R**
---
## ⭐ If you found this project useful, consider giving it a start
