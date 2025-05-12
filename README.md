---

# 📈 YouTube Subscriber Prediction using Machine Learning

This project focuses on building a machine learning model to predict the number of YouTube subscribers for a channel based on historical data and various growth metrics. The model helps estimate future subscriber counts and can assist creators and analysts in tracking audience growth trends.

---

## 🔍 Problem Statement

With the rapid rise of social media platforms like YouTube, predicting subscriber growth has become valuable for content strategy and marketing. Given the huge volume of content and creators, it is essential to forecast subscriber growth to make data-driven decisions. This project aims to develop a model that accurately predicts subscriber count based on historical and other relevant channel features.

---

## ✅ Proposed Solution

* Use a cleaned and preprocessed dataset containing YouTube channel metrics.
* Apply regression-based deep learning models to predict subscriber growth.
* Evaluate model performance using Mean Squared Error (MSE) and Accuracy.
* Visualize the prediction performance using plots.

---

## 🧠 Algorithms Used

* **Model**: Dense Neural Network (Regression)
* **Optimizer**: Adam
* **Loss Function**: Mean Squared Error (MSE)
* **Evaluation Metrics**: Accuracy, MSE

---

## 🔧 Tech Stack

* **Language**: Python
* **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow / Keras

---

## 📊 Results

* **Training Accuracy**: \~99.9%
* **Final MSE**: \~422
* The model performs well even for large-scale prediction (in millions), with acceptable prediction differences.

---

## 📁 Project Structure

```
📦 youtube-subscriber-prediction
├── 📄 subscriber_prediction.ipynb
├── 📄 requirements.txt
├── 📊 results/
│   └── loss_accuracy_plots.png
├── 📄 README.md
└── 📂 dataset/
    └── youtube_data.csv
```

---

## 📈 Future Scope

* Add more updated YouTube data (2025+)
* Integrate real-time analytics using YouTube APIs
* Apply more advanced models (e.g., LSTM, XGBoost)
* Expand to prediction across multiple social platforms (Instagram, TikTok)

---

## 🔗 Dataset Source

* [Kaggle Dataset Link](https://www.kaggle.com/datasets/amansingh0000000/youtube-2025-dataset/data)
---
