# 🚀 Real-Time Context-Aware Text Classification & Live Stream Routing

An intelligent machine learning system that classifies customer feedback into the correct department and routes each message in real time while assigning dynamic priority levels based on the message context.

---

## 📖 Project Overview

Customer support teams receive thousands of customer messages every day through emails, chats, websites, and mobile applications.

Reading and forwarding every message manually takes time and often leads to delays.

This project automates the entire workflow using Machine Learning.

The system:

- Reads customer feedback
- Predicts the feedback category
- Detects urgency
- Assigns a priority
- Routes the message to the correct department
- Simulates a real-time message stream

---

## 🎯 Objectives

- Automatically classify customer feedback
- Route messages to the correct department
- Detect urgent customer issues
- Simulate real-time message processing
- Save the trained model for deployment

---

## 📂 Dataset

Dataset Name:

```
customer_feedback.csv
```

Contains:

- 1000 customer feedback messages
- 5 balanced categories
- No missing values

Categories include:

- Billing
- Delivery
- Product
- Technical Support
- General Inquiry

---

## ⚙️ Machine Learning Pipeline

### 1. Data Exploration

- Category Distribution
- Message Length Analysis
- Word Clouds

---

### 2. Text Preprocessing

- Lowercase Conversion
- Remove punctuation
- Remove extra spaces

---

### 3. Feature Engineering

TF-IDF Vectorizer

Uses:

- Unigrams
- Bigrams

---

### 4. Model Training

Three ML models were trained.

- Multinomial Naive Bayes
- Logistic Regression
- Linear SVM

The best model was automatically selected using Macro F1 Score.

---

### 5. Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

### 6. Context-Aware Priority Detection

Priority is assigned based on:

- Feedback category
- Urgent keywords
- Prediction confidence

Priority Levels:

- Low
- Medium
- High
- Critical

---

### 7. Real-Time Stream Simulation

Incoming customer messages are processed one by one.

For each message the system predicts:

- Category
- Confidence Score
- Priority
- Destination Team

---

### 8. Live Dashboard

Visualizes:

- Messages routed per department
- Messages by priority level

---

### 9. Model Saving

The trained pipeline is stored using Joblib.

```
feedback_router_model.joblib
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud
- Joblib
- Jupyter Notebook

---

## 📁 Project Structure

```
Real-Time-Context-Aware-Text-Classification/

│
├── ML_TASK_4_solution.ipynb
├── customer_feedback.csv
├── feedback_router_model.joblib
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Real-Time-Context-Aware-Text-Classification.git
```

Move into the folder

```bash
cd Real-Time-Context-Aware-Text-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook ML_TASK_4_solution.ipynb
```

---

## 📈 Results

- High classification accuracy
- Real-time routing simulation
- Dynamic priority detection
- Automatic department assignment

---

## 💡 Future Improvements

- Deep Learning models
- BERT embeddings
- Kafka integration
- RabbitMQ streaming
- Flask/FastAPI deployment
- Web Dashboard
- Continuous retraining

---

## 👨‍💻 Author

**Mohamed Al Zameer**

AI Developer | Web Developer

GitHub:
https://github.com/yourusername

LinkedIn:
https://linkedin.com/in/yourprofile

---

## ⭐ If you found this project useful

Please give this repository a ⭐ on GitHub.
