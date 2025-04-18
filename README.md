# 🔍 Credit Card Fraud Detection using Machine Learning

Detecting fraudulent transactions is one of the most crucial challenges in the financial industry. This project aims to build an efficient machine learning classification model to identify credit card fraud by analyzing transaction behavior, amount, and patterns.

## 📌 Problem Statement

Credit card fraud leads to billions of dollars in global financial losses each year. Fraudulent transactions are rare and difficult to detect due to their similarity to legitimate behavior. The challenge lies in handling a highly imbalanced dataset and building a model that can identify fraudulent patterns without too many false alarms.

## 🧠 Methodology

1. **Data Collection**  
   - Dataset `creditcard.csv` uploaded via Google Colab.

2. **Preprocessing**  
   - Scaled numerical features (`Time` and `Amount`) using `StandardScaler`.  
   - Dropped the original unscaled columns.

3. **Feature Engineering**  
   - Reorganized columns for better data structure.  
   - Separated input features (X) and target (`Class` column).

4. **Handling Imbalanced Data**  
   - Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the class distribution.

5. **Model Training**  
   - Used **Random Forest Classifier**, known for its accuracy and robustness on imbalanced data.

6. **Model Evaluation**  
   - Evaluated performance using **accuracy, precision, recall**, and **confusion matrix** heatmap.

## 📊 Results

- The model shows high precision and recall for fraud detection after applying SMOTE.
- Visualized performance using seaborn heatmap for the confusion matrix.

## 📁 Files

- `creditcard.csv`: Dataset containing anonymized credit card transactions.
- `fraud_detection.ipynb`: Colab notebook with full data pipeline, model training, and evaluation.

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn` (scikit-learn)
- `imblearn` (for SMOTE)

## 🖼️ Visuals

![Confusion Matrix Heatmap](https://i.imgur.com/your_confusion_matrix_image.png)  
*(Replace with your actual image link if uploading visuals)*

---

## 🚀 How to Run

1. Open the notebook in **Google Colab**
2. Upload the dataset `creditcard.csv` when prompted
3. Run all cells to train and evaluate the model

---

## 📬 Contact

For queries or collaborations, reach out to **Preeti Tiwari**.

# Predicting-Credit-Card-Fraud3
