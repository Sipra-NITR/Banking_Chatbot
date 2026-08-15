# 🏦 Banking Support Chatbot using Machine Learning

A Banking Support Chatbot built using **Python, Machine Learning, Scikit-learn, and Gradio**. The chatbot classifies customer banking queries into different categories and provides an appropriate response based on the predicted category.

---

## 📌 Features

- Text preprocessing using NLTK
- TF-IDF Vectorization
- Naive Bayes Classification
- Banking query classification
- Automatic response generation
- Interactive chatbot interface using Gradio
- Data visualization using Matplotlib and Seaborn
- Model evaluation using Accuracy, Classification Report, and Confusion Matrix

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio

---

## 📂 Dataset

The chatbot is trained on a banking support dataset containing:

- Ticket ID
- Priority
- Category
- Customer Question
- Support Response

### Sample Categories

- Account
- Debit Card
- Credit Card
- UPI
- ATM
- Net Banking
- Mobile Banking
- Loan
- EMI
- Fixed Deposit (FD)
- Recurring Deposit (RD)
- KYC
- Fraud
- Cheque Book
- Statement

---

## 📊 Machine Learning Pipeline

1. Load Banking Support Dataset
2. Data Exploration
3. Text Cleaning
   - Lowercasing
   - Remove punctuation
   - Remove stopwords
4. TF-IDF Feature Extraction
5. Train-Test Split
6. Train Multinomial Naive Bayes Classifier
7. Evaluate Model
8. Deploy Chatbot using Gradio

---

## 📈 Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Sipra-NITR/banking-support-chatbot.git
```

Move into the project directory

```bash
cd banking-support-chatbot
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python chatbot.py
```

or if using Google Colab, simply run all notebook cells.

---

## 📁 Project Structure

```
Banking-Support-Chatbot/
│
├── banking_support_dataset.csv
├── chatbot.py
├── requirements.txt
├── README.md

```

---

## 💬 Example Queries

- My debit card is blocked.
- I forgot my internet banking password.
- How do I apply for a personal loan?
- My UPI payment failed.
- I need a new cheque book.
- How can I update my KYC?
- Download my account statement.
- Where is the nearest ATM?

---

## 📷 Sample Output

**Input**

```
My debit card is blocked.
```

**Predicted Category**

```
Debit Card
```

**Response**

```
Please block your debit card immediately and request a replacement through the mobile banking app or by contacting customer support.
```

---

##Screenshots
--HomePage-->Screenshots/HomePage.png
--ResultPage-->Screenshots/ResultPage.png


## 🔮 Future Enhancements

- Deep Learning (LSTM/BERT)
- Voice-based chatbot
- Multilingual support
- Live banking API integration
- Sentiment analysis
- User authentication
- Context-aware conversations

---

## 👩‍💻 Author

**Sipra Sworupa Mishra**

B.Tech Student | Machine Learning & Full Stack Development Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository!
