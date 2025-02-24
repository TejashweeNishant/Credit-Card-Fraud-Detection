Credit Card Fraud Detection using Deep Learning
🚀 Overview
This project implements a Credit Card Fraud Detection System using Artificial Neural Networks (ANN). The model is trained on an imbalanced dataset and utilizes SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance. The model is built using TensorFlow/Keras and achieves high accuracy in detecting fraudulent transactions.
📌 Features
✅ Data Preprocessing

Standardizes transaction amounts and timestamps using StandardScaler.
Removes unnecessary columns for better feature representation.
✅ Handling Class Imbalance

Uses SMOTE to balance the dataset and improve fraud detection.
✅ Artificial Neural Network (ANN) Model

Input Layer: 16 neurons, ReLU activation
Hidden Layer: 8 neurons, ReLU activation
Dropout Layers: Prevents overfitting
Output Layer: 1 neuron, Sigmoid activation
✅ Evaluation Metrics

Accuracy, Precision, Recall, F1-score
Confusion Matrix
AUC-ROC Score
✅ Visualization

Training & Validation Accuracy Graph
Confusion Matrix for Model Performance
📊 Dataset
The dataset contains transactions labeled as fraudulent (1) or legitimate (0).
It is highly imbalanced, requiring SMOTE for fair training.


🔥 Model Performance:
Metric	Score
Accuracy	99.86%
Precision	97.82%
Recall	98.53%
F1-Score	98.17%
AUC-ROC Score	99.74%


📊 Results & Visualization
🔹 Training & Validation Accuracy
The model's accuracy steadily improves over 10 epochs.
🔹 Confusion Matrix
The confusion matrix shows true positives, false positives, true negatives, and false negatives.


💡 Future Improvements
🔹 Optimize hyperparameters (learning rate, batch size, epochs)
🔹 Implement feature engineering for better fraud detection
🔹 Deploy as a Web App using Flask, FastAPI, or Streamlit
🔹 Use Autoencoders for Anomaly Detection


📝 License: 
This project is MIT licensed. Feel free to modify and use it.

📩 Contact:
📧 Email:  tejnishdhiran@gmail.com
