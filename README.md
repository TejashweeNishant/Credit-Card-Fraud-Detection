Credit Card Fraud Detection using Deep Learning

🚀 A deep learning-based solution for detecting fraudulent credit card transactions using **Artificial Neural Networks (ANNs)** and **SMOTE (Synthetic Minority Over-sampling Technique)** to handle class imbalance.  

📌 Project Overview
Credit card fraud is a growing concern in financial security. This project leverages deep learning techniques to detect fraudulent transactions with high accuracy. The model is trained using **ANNs** and enhanced with **SMOTE** to balance the dataset, ensuring better fraud detection performance.  

⚡ Features  
✔️ **Preprocessing**: Standardizes transaction amounts and timestamps  
✔️ **Class Balancing**: Uses **SMOTE** to handle fraud cases (highly imbalanced data)  
✔️ **Deep Learning Model**: Implements **ANN with ReLU activation & Dropout** for better generalization  
✔️ **Performance Metrics**: Evaluates accuracy, confusion matrix, and **AUC-ROC score**  

📁 Dataset 
- The dataset used is **[Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)** from Kaggle  
- It contains **284,807 transactions** with **492 fraudulent transactions (0.17%)**  
- Features include **time, amount, and 28 anonymized PCA features**  

⚙️ Installation  
Clone this repository and install the required dependencies:  

```bash
git clone https://github.com/TejashweeNishant/Credit-Card-Fraud-Detection.git  
cd Credit-Card-Fraud-Detection  
pip install -r requirements.txt  
```

🏗 Model Architecture  
The ANN model consists of:  
- Input Layer: 30 features (after preprocessing)  
- Hidden Layers:  
- 16 neurons (ReLU activation) + Dropout (0.5) 
- 8 neurons (ReLU activation) + Dropout (0.5)  
- Output Layer: 1 neuron (Sigmoid activation for binary classification)  

🚀 Usage 
Run the model using:  
```bash
python fraud_detection.py
```
Expected Output
Training Accuracy: ~99.8%  
- Validation Accuracy: ~99.6%  
- AUC-ROC Score: ~0.999  

📊 Results:
- Confusion Matrix
- Classification Report
- AUC-ROC Curve
(These are printed after running the script)  

🔥 Contributing 
Feel free to fork this repo and submit pull requests! Contributions are welcome.  

📜 License 
This project is licensed under the MIT License.  

