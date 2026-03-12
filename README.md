# 🚀 NLP App — Flask NLP Web Application

A **Flask-based Natural Language Processing (NLP) web application** that allows users to analyze text using multiple NLP capabilities such as **Named Entity Recognition (NER)**, **Sentiment Analysis**, and **Abuse Detection**.

The system provides a **simple web interface with authentication** where users can log in and perform multiple NLP analyses using Python NLP libraries.

This project demonstrates **backend web development**, **NLP integration**, and **modular Flask architecture**.

---

## 🚀 Features

- 🔐 **User authentication system**
- 🏷 **Named Entity Recognition (NER)**
- 💬 **Sentiment analysis using TextBlob**
- ⚠️ **Abuse detection module**
- 📊 **Interactive web interface for NLP analysis**
- ⚡ **Flask-based backend application**
- 📦 **JSON-based user data storage**

---

## 🧠 What This Project Demonstrates

This project highlights the following **backend and NLP engineering skills**:

- **Flask web application development**
- **Natural Language Processing integration**
- **Text analysis using TextBlob and NLTK**
- **User authentication system implementation**
- **Web-based NLP tool development**
- **Separation of backend logic and templates**

---

## 📂 Project Structure

```
NLP_WEBSITE_FLASK/
│
├── app.py                 # Main Flask application
├── api.py                 # NLP processing logic
├── db.py                  # User authentication module
├── users.json             # JSON user database
├── requirements.txt       # Python dependencies
│
├── templates/             # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── profile.html
│   ├── ner.html
│   ├── sentiment.html
│   └── abuse_detection.html
│
├── static/                # Static files (CSS, JS)
│
├── .gitignore
└── README.md
```

---

## ⚙️ Architecture Overview

The application follows a **simple Flask MVC-style architecture**.

```
User Request
     │
     ▼
Flask Server (app.py)
     │
     ▼
API Layer
(api.py)
     │
     ▼
NLP Processing
(TextBlob / NLTK)
     │
     ▼
Response Rendered
(HTML Templates)
```

### Design Principles

- **Separation of Concerns**
- **Reusable NLP modules**
- **Simple authentication architecture**
- **Clean template-based UI rendering**

---

## 📊 NLP Functional Modules

The application includes multiple **NLP analysis modules**.

### Named Entity Recognition

- Extracts **noun phrases and entities**
- Identifies:
  - *People*
  - *Locations*
  - *Organizations*

Implemented using **NLTK**.

---

### Sentiment Analysis

Evaluates **sentiment polarity** of input text using **TextBlob**.

Returns:

- Positive sentiment
- Negative sentiment
- Neutral sentiment

---

### Abuse Detection

Detects **abusive or offensive language** within the provided text.

*Note: This feature is currently under development and will be expanded in future updates.*

---

## ⚠️ Planned Future Features

The system architecture allows additional NLP features to be added easily.

Potential future modules:

- Emotion detection
- Text summarization
- Topic modeling
- Chatbot interface
- Toxic comment detection
- NLP API endpoints

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/your-username/nlp-app.git
cd nlp-app
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Download required NLTK resources

```bash
python -m nltk.downloader punkt averaged_perceptron_tagger maxent_ne_chunker words
```

---

## ▶️ Running the Application

Start the Flask server:

```bash
python app.py
```

Server will run at:

```
http://127.0.0.1:5000/
```

Open the URL in your browser to access the application.

---

## 🧪 Example Usage

Example workflow:

1. **User registers or logs into the application**
2. User accesses the **profile dashboard**
3. User selects an **NLP analysis tool**
4. User submits text for analysis
5. The system processes text using **NLP libraries**
6. Results are displayed in the **web interface**

---

## 📈 Potential Improvements

Future enhancements could include:

- NLP API endpoints
- Deep learning NLP models
- Database integration (PostgreSQL / MongoDB)
- User analytics dashboard
- Docker containerization
- Cloud deployment (AWS / Render / Railway)

---

## 🧰 Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Programming language |
| Flask | Web framework |
| NLTK | Named entity recognition |
| TextBlob | Sentiment analysis |
| JSON | User data storage |
| HTML/CSS | Frontend interface |
| Jinja2 | Template rendering |

---

## 🎯 Learning Outcomes

This project helped build understanding of:

- **Flask web application development**
- **Natural Language Processing pipelines**
- **User authentication systems**
- **Python modular architecture**
- **Web-based NLP systems**

---

## 👤 Author

**Rudra**

B.Tech Final Year Student  
Aspiring **MLOps Engineer**
