**🚀 NLP App — Flask NLP Web Application**

A Flask-based Natural Language Processing (NLP) web application that allows users to analyze text using multiple NLP capabilities such as:

Named Entity Recognition (NER)

Sentiment Analysis

Abuse Detection

The application also includes a basic authentication system, allowing users to register and log in before accessing the NLP tools.

**📌 Overview**

This project demonstrates how web development and Natural Language Processing can be integrated into a single application.

Users interact with a Flask-powered web interface where they can submit text and perform multiple NLP analyses using libraries such as NLTK and TextBlob.

**✨ Features**
_🔐 User Authentication_

Register new users using name, email, and password

Login system for existing users

User data stored in a JSON-based database

_🏷 Named Entity Recognition (NER)_

Extracts noun phrases and named entities from user-provided text

Identifies entities such as:

People

Locations

Organizations

Implemented using NLTK

_💬 Sentiment Analysis_

Evaluates sentiment polarity of the input text

Uses TextBlob for sentiment detection

Note: This feature is currently a placeholder and will be fully implemented in a future update.

_⚠️ Abuse Detection_

Detects abusive or offensive language within user-provided text

Note: This feature is planned and will be implemented in future updates.

_👤 User Profile Dashboard_

After logging in, users can:

Access available NLP tools

Submit text for analysis

View processed results directly within the web interface

**🧰 Technologies Used**
| **Layer**             | **Technology** |
| --------------------- | -------------- |
| **Backend**           | Flask          |
| **NLP Libraries**     | TextBlob, NLTK |
| **Data Storage**      | JSON           |
| **Frontend**          | HTML, CSS      |
| **Templating Engine** | Jinja2         |


**⚙ Installation**

1️⃣ Clone the Repository

git clone https://github.com/your-username/nlp-app.git

Navigate to the project directory:

cd nlp-app

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Download Required NLTK Resources

python -m nltk.downloader punkt averaged_perceptron_tagger maxent_ne_chunker words

▶️ Running the Application


Start the Flask server:

python app.py


Open your browser and visit:

http://127.0.0.1:5000/

## 📂 Project Structure

```
nlp_web/
│
├── app.py
├── api.py
├── db.py
├── users.json
├── requirements.txt
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── profile.html
│   ├── ner.html
│   ├── sentiment.html
│   └── abuse_detection.html
│
├── static/
│
├── .gitignore
└── README.md
```

📊 Example Workflow

User registers or logs into the application

User accesses the dashboard

User selects an NLP analysis tool

Text is processed using NLP libraries

Results are displayed within the web interface


🤝 Contribution

Contributions are welcome.

To contribute:

Fork the repository

Create a new branch

Commit your changes

Submit a pull request

You can also open an Issue if you find bugs or want to suggest improvements.


📄 License

This project is licensed under the MIT License.
See the LICENSE file for more details.
