# 🛡️ Phishing Website Detection System

A machine learning-based web application that analyzes website URLs and predicts whether they may be **phishing or legitimate**. Built with Python and Streamlit, the application extracts URL-based features and uses a trained XGBoost classifier to make predictions.

🚀 **Live Demo:** [Try the Phishing Detection App](https://phishing-detection-app-hbwhgfcxydeme37cksrb9w.streamlit.app/)

## 🚀 Features

- Detects potentially phishing URLs
- Interactive web interface built with Streamlit
- URL-based feature extraction
- Machine learning-based classification using XGBoost
- Real-time prediction when a URL is submitted
- Research and training notebooks for model development

## 🧰 Technologies Used

- **Language:** Python
- **Web Framework:** Streamlit
- **Machine Learning:** XGBoost, Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Development:** Jupyter Notebook, Git, GitHub

## 📂 Project Structure

```text
phishing-detection-app/
├── app.py
├── requirements.txt
├── XGBoostClassifier.pickle
├── README.md
├── training/
│   ├── Phishing Website Detection_Models & Training.ipynb
│   └── URL Feature Extraction.ipynb
└── DataFiles/
    ├── 1.Benign_list_big_final.csv
    ├── 2.online-valid.csv
    ├── 3.legitimate.csv
    ├── 4.phishing.csv
    └── 5.urldata.csv
```

*The structure above is the planned organization. The training folder and datasets should be added to GitHub before describing them as included files.*

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/bussavarun9/phishing-detection-app.git
```

### 2. Open the project folder

```bash
cd phishing-detection-app
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the application

```bash
streamlit run app.py
```

## 🔍 How It Works

1. The user enters a website URL.
2. The application extracts URL-based features.
3. The extracted features are passed to the trained XGBoost model.
4. The model predicts whether the URL is classified as phishing or legitimate.
5. The application displays the prediction.

## 🧠 Machine Learning Concepts

- Supervised learning
- Classification
- Feature extraction
- Gradient boosting
- XGBoost classifier
- Phishing URL detection

## 📓 Training and Research

The original project includes Jupyter notebooks for URL feature extraction and machine learning model training, along with datasets used for development and experimentation.

## 👨‍💻 Author

**Varun Bussa**

Computer Science and Engineering student interested in machine learning, software development, and web technologies.

## 🔮 Future Improvements

- Improve feature extraction and prediction accuracy
- Add additional phishing detection techniques
- Enhance the user interface and user experience
- Integrate reliable threat intelligence sources
- Add model evaluation metrics and performance comparisons

## ⚠️ Disclaimer

This project is for educational and research purposes. Predictions are model estimates and do not guarantee that a website is safe or malicious And 
This project is showcased solely for portfolio and skill-demonstration purposes. Please do not copy, reproduce, or redistribute the project without my permission.

