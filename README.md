# TruthPulse AI – Fake News and Fake Facts Detection

## 📌 Project Overview

**TruthPulse AI** is a machine learning-based application designed to detect fake news and fabricated facts using Natural Language Processing (NLP) techniques. It analyzes user-provided text and classifies the content as **Real** or **Fake**.

The system uses TF-IDF for feature extraction and Logistic Regression for classification. It also provides a simple, user-friendly graphical interface developed using Tkinter, allowing users to check information quickly. The application is designed to work offline without requiring high-end hardware.

The project also includes mathematical expression evaluation functionality as described in the implementation report.

## 🎯 Objectives

- Develop a unified system for detecting fake news and fake facts.
- Collect and combine real and fake news and facts datasets.
- Perform text preprocessing and cleaning.
- Extract relevant features using TF-IDF.
- Train a Logistic Regression classification model.
- Evaluate performance using accuracy, precision, recall, F1-score, and a confusion matrix.
- Develop an interactive GUI using Tkinter.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **NLP:** TF-IDF Vectorizer
- **Classification Algorithm:** Logistic Regression
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **GUI Development:** Tkinter
- **Model Saving:** Joblib

## ⚙️ Project Workflow

1. **Data Collection:** Combine real and fake news and facts datasets.
2. **Data Preprocessing:** Convert text to lowercase and remove punctuation, numbers, special characters, and unnecessary content.
3. **Feature Extraction:** Convert text into numerical features using TF-IDF.
4. **Model Training:** Train the Logistic Regression classifier.
5. **Prediction:** Classify the entered text as Real or Fake.
6. **GUI Output:** Display the prediction through the Tkinter interface.

## 📂 Dataset

The project uses the following datasets:

- `True.csv` – Real news articles.
- `Fake.csv` – Fake news articles.
- `final_fake_facts_dataset.csv` – Fake factual statements.
- `enhanced_real_facts.csv` – Real factual statements.

The datasets are combined to create a unified training dataset for classification.

## 📊 Model Performance

According to the project report, the model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 98.97% |
| Precision | 99% |
| Recall | 99% |
| F1-Score | 99% |
| Average Prediction Time | Under 0.5 seconds |

The report also includes a confusion matrix to evaluate the classification performance.

*Note: These are the results documented in the project report.*

## 💻 Hardware Requirements

- Processor: Intel Core i3 or higher
- RAM: Minimum 4 GB
- Storage: Minimum 2 GB free space
- GPU: Not required

## 📦 Software Requirements

- Python 3.8 or later
- Windows / Linux / macOS
- Jupyter Notebook or VS Code

## 🚀 Installation and Execution

**1. Clone the repository**

```bash
git clone https://github.com/your-username/TruthPulse-AI.git
```

**2. Navigate to the project folder**

```bash
cd TruthPulse-AI
```

**3. Install the required libraries**

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

**4. Run the application**

Run the provided Jupyter Notebook to execute the model workflow. If the repository includes a standalone Tkinter application, run it using:

```bash
python app.py
```

*Make sure the dataset files and trained model files are available in their required locations.*

## ✨ Key Features

- Detects fake news and fabricated facts.
- Uses machine learning and NLP techniques.
- TF-IDF-based text feature extraction.
- Logistic Regression classification.
- Simple and interactive Tkinter GUI.
- Offline functionality.
- Lightweight and fast predictions.
- Mathematical expression evaluation functionality.

## ⚠️ Limitations

- Currently supports English text.
- Predictions depend on the quality and diversity of training datasets.
- May struggle with sarcasm, satire, and complex contextual statements.
- Does not independently verify the original source or publisher.
- Supports text-based input rather than image and video analysis.
- May produce false-positive or false-negative predictions.

## 🔮 Future Enhancements

- Integrate advanced NLP models such as BERT and RoBERTa.
- Add multilingual support.
- Introduce speech-to-text functionality.
- Extend detection to images and videos.
- Integrate real-time fact-checking APIs.
- Develop a web or mobile application.

## 🎓 Project Information

**Project:** TruthPulse AI  
**Domain:** Artificial Intelligence, Machine Learning and Natural Language Processing  
**Application:** Fake News and Fake Facts Detection  
**Institution:** Mysore University School of Engineering, University of Mysore

## 📄 Conclusion

TruthPulse AI provides a lightweight and user-friendly approach to identifying misinformation through machine learning. By combining TF-IDF feature extraction, Logistic Regression classification, and a Tkinter-based graphical interface, the system helps users assess textual information as Real or Fake.

---

**TruthPulse AI – Promoting Awareness and Combating Misinformation Through AI.**
