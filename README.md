# 🛡️ Phishing URL Detection using Machine Learning

## 📌 Project Overview
This project is a Machine Learning classification model designed to detect and classify malicious, phishing, and safe URLs. With the increasing number of cyber threats, identifying deceptive links is crucial. This model analyzes the structural properties of URLs and uses Natural Language Processing (NLP) techniques to predict their safety.

**Status:** Ongoing

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, Scikit-learn (Logistic Regression, TF-IDF Vectorizer)

## ⚙️ Machine Learning Pipeline
1. **Data Collection & Loading:** Imported a comprehensive dataset of URLs categorized as benign, phishing, and defacement.
2. **Exploratory Data Analysis (EDA):** Analyzed the distribution of safe vs. malicious links and extracted features like URL length.
3. **Text Vectorization:** Converted raw text URLs into numerical format using **TF-IDF (Term Frequency-Inverse Document Frequency)** to prepare the data for the machine learning model.
4. **Model Training:** Split the data into training (80%) and testing (20%) sets. Trained a **Logistic Regression** model to identify patterns in malicious URLs.
5. **Evaluation:** Tested the model's predictive power on unseen data.

## 📊 Results & Accuracy
The model successfully learned the distinction between normal and phishing URLs, achieving an impressive accuracy score.
* **Final Model Accuracy:** **94.80%**

## 💡 Future Scope
* Implement more advanced algorithms (like Random Forest or XGBoost) to compare accuracy.
* Build a simple web interface or browser extension to test real-time URLs.
*
