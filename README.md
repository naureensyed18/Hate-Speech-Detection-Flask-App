# 🛡️ Hate Speech Detection Flask App

A web-based application that uses Natural Language Processing (NLP) and Machine Learning to detect hate speech in text input.

---

## 🚀 Features

- Detects hate speech vs. normal text
- Built with Flask (Python backend)
- Machine Learning model trained with scikit-learn
- TF-IDF vectorization + Logistic Regression
- Frontend with simple HTML + CSS

---

## 🗂️ Project Structure

```
Hate-Speech-Detection-Flask-App/
├── app.py
├── train_model.py
├── model/
│   ├── model.pkl
│   └── vectorizer.pkl
├── data/
│   └── hate_speech_dataset.csv
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repo

```bash
git clone https://github.com/your-username/Hate-Speech-Detection-Flask-App.git
cd Hate-Speech-Detection-Flask-App
```

### 2. Create virtual environment (optional)

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

> Note: Also run `nltk.download('stopwords')` if using NLTK stopwords.

---

## 🧠 Train the Model

```bash
python train_model.py
```

This will generate:
- `model/model.pkl`
- `model/vectorizer.pkl`

---

## 🌐 Run the App

```bash
python app.py
```

Open your browser at [http://localhost:5000](http://localhost:5000)

---

## 📄 License

MIT License

---

## 👩‍💻 Author

**Naureen Syed**  
🔗 [GitHub](https://github.com/naureensyed18) | [LinkedIn](https://www.linkedin.com/in/naureen-syed-574a33212)
