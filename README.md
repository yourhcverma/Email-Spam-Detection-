# 📧 Email Spam Detection

A machine learning project that classifies emails as **spam** or **ham** (not spam) using multiple classification algorithms and NLP techniques.

## 👥 Team Members

| Name    | Roll Number |
|---------|-------------|
| Taashif | 22347       |
| Aman    | 22043       |
| Vivek   | 22373       |

## 📌 Project Overview

This project builds and compares multiple ML models to automatically detect spam emails. The pipeline includes:

1. **Data Loading & Exploration** – Understanding the dataset structure and class distribution
2. **Text Preprocessing** – Cleaning email text using regex, tokenization, and normalization
3. **Feature Engineering** – TF-IDF vectorization to convert text into numerical features
4. **Model Training** – Training and comparing four classification algorithms
5. **Evaluation** – Confusion matrix and classification report for each model

## 🧠 Models Used

| Model                     | Description                                      |
|---------------------------|--------------------------------------------------|
| **Multinomial Naive Bayes** | Probabilistic classifier well-suited for text data |
| **Logistic Regression**     | Linear model for binary classification            |
| **Random Forest**           | Ensemble of decision trees for robust predictions |
| **Support Vector Machine (SVM)** | Finds optimal hyperplane to separate classes  |

## 📊 Dataset

- **File**: `spam_ham_dataset3.csv`
- **Columns**: `label` (ham/spam), `text` (email content), `label_num` (0 = ham, 1 = spam)
- **Source**: [Spam/Ham Email Dataset on Kaggle](https://www.kaggle.com/datasets)

> ⚠️ The dataset file is not included in this repository due to size constraints. You can download it from the link above and place it in the project root directory.

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization
  - `wordcloud` – Word cloud generation
  - `scikit-learn` – ML models, TF-IDF, train/test split, evaluation metrics
  - `scipy` – Sparse matrix operations
  - `re` – Text preprocessing with regular expressions

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourhcverma/Email-Spam-Detection-.git
   cd Email-Spam-Detection-
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud scikit-learn scipy
   ```

3. **Add the dataset**
   - Download `spam_ham_dataset3.csv` and place it in the project root directory.

4. **Run the notebook**
   - Open `DSP_CODE_taashif_22347_aman_22043_vivek_22373_emailspamdetection.ipynb` in Jupyter Notebook or Google Colab.
   - Run all cells sequentially.

## 📁 Project Structure

```
├── DSP_CODE_taashif_22347_aman_22043_vivek_22373_emailspamdetection.ipynb   # Main code notebook
├── DSP_ppt_taashif_22347_Aman_22043_vivek_22373.pptx                       # Project presentation
├── DSP_report_taashif_22347_aman_22035_vivek_22373_emailspamdetection.pdf   # Project report
├── READMEFILE_taashif_22347_Aman_22043_vivek_22373_email_spam_detection.pdf # Detailed README (PDF)
└── README.md                                                                # This file
```

## 📄 License

This project is for academic/educational purposes.
