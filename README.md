**🧠 NLP App with Tkinter**

A GUI-based Natural Language Processing application built using Python and Tkinter.
The application allows users to perform multiple NLP tasks such as Sentiment Analysis, Named Entity Recognition (NER), and Emotion Prediction on user-provided text.

**✨ Features**
_🔐 User Authentication_

Register new users

Login with existing credentials# 🧠 NLP App with Tkinter

A **GUI-based Natural Language Processing application** built using **Python and Tkinter**.

The application allows users to perform multiple **NLP tasks** such as **Sentiment Analysis**, **Named Entity Recognition (NER)**, and **Emotion Prediction** on user-provided text.

This project demonstrates **desktop GUI development**, **NLP integration**, and **modular Python architecture**.

---

## 🚀 Features

- 🔐 **User authentication system**
- 💬 **Sentiment analysis using TextBlob**
- 🏷 **Named Entity Recognition using NLTK**
- 😊 **Emotion prediction module**
- 🖥 **Interactive desktop GUI using Tkinter**
- 📦 **JSON-based user data storage**
- 🧩 **Modular Python application design**

---

## 🧠 What This Project Demonstrates

This project highlights the following **software development and NLP skills**:

- **Desktop GUI application development using Tkinter**
- **Natural Language Processing integration**
- **Text sentiment analysis using TextBlob**
- **Entity extraction using NLTK**
- **Simple authentication system with JSON storage**
- **User-friendly NLP interface design**

---

## 📂 Project Structure

```
NLP_TKINTER_APP/
│
├── nlp_app.py             # Main application entry point
├── nlp_engine.py          # NLP processing logic
├── auth.py                # User authentication module
├── users.json             # JSON user database
│
├── assets/                # UI resources (optional)
│
├── .gitignore
└── README.md
```

---

## ⚙️ Architecture Overview

The application follows a **simple modular architecture**.

```
User Interaction
       │
       ▼
Tkinter GUI
       │
       ▼
Application Logic
(nlp_app.py)
       │
       ▼
NLP Processing
(TextBlob / NLTK)
       │
       ▼
Results Displayed
on GUI Interface
```

### Design Principles

- **Separation of Concerns**
- **Reusable NLP modules**
- **Simple authentication system**
- **User-friendly desktop interface**

---

## 📊 NLP Functional Modules

### 💬 Sentiment Analysis

Uses **TextBlob** to evaluate sentiment properties such as:

- polarity
- subjectivity

Provides quick insights into whether text is **positive, negative, or neutral**.

---

### 🏷 Named Entity Recognition (NER)

Implemented using **NLTK**.

Detects entities such as:

- *People*
- *Locations*
- *Organizations*
- *Other named entities*

---

### 😊 Emotion Prediction

Detects emotional tone by matching words against **predefined emotion categories**:

- Happy
- Sad
- Angry
- Surprised

---

## ⚠️ Potential Future Enhancements

The application architecture allows additional NLP features to be integrated easily.

Possible improvements:

- Deep learning-based emotion detection
- Text summarization
- Language detection
- Chatbot interface
- Speech-to-text integration

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/your-username/nlp-app.git
cd nlp-app
```

### Install required libraries

```bash
pip install textblob nltk
```

### Download required NLTK resources

```bash
python -m nltk.downloader punkt averaged_perceptron_tagger maxent_ne_chunker words
```

---

## ▶️ Running the Application

Run the application:

```bash
python nlp_app.py
```

The **Tkinter GUI interface** will open where users can interact with the NLP tools.

---

## 🧪 Example Usage

Typical workflow:

1. **User registers or logs into the application**
2. User opens the **main NLP dashboard**
3. User enters text into the analysis field
4. User selects an NLP function
5. The system processes the text using **TextBlob or NLTK**
6. Results are displayed within the **GUI interface**

---

## 📈 Potential Improvements

Future enhancements could include:

- GUI redesign using **CustomTkinter**
- Deep learning NLP models
- SQLite database integration
- Export analysis results to files
- NLP visualization dashboard
- Packaging as a desktop application (.exe)

---

## 🧰 Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Programming language |
| Tkinter | GUI framework |
| TextBlob | Sentiment analysis |
| NLTK | Named entity recognition |
| JSON | User data storage |

---

## 🎯 Learning Outcomes

This project helped build understanding of:

- **Desktop GUI application development**
- **Natural Language Processing pipelines**
- **User authentication systems**
- **Python modular architecture**
- **Interactive NLP tools**

---

## 👤 Author

**Rudra**

B.Tech Final Year Student  
Aspiring **MLOps Engineer**

User data stored in a JSON-based database

_💬 Sentiment Analysis_

Uses TextBlob to evaluate:

polarity

subjectivity

Provides quick insight into the sentiment of the input text.

_🏷 Named Entity Recognition (NER)_

Utilizes NLTK to detect entities such as:

People

Locations

Organizations

Other named entities

_😊 Emotion Prediction_

Detects emotional tone by matching words to predefined emotion categories:

Happy

Sad

Angry

Surprised

**🧰 Technologies Used**

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Python     | Core programming language |
| Tkinter    | GUI framework             |
| TextBlob   | Sentiment analysis        |
| NLTK       | Named entity recognition  |
| JSON       | User data storage         |


**⚙ Installation**
_1️⃣ Prerequisites_

Make sure Python 3.x is installed.

Install required libraries:

pip install textblob nltk


_2️⃣ Clone the Repository_

git clone https://github.com/your-username/nlp-app.git

Navigate to the project directory:

cd nlp-app

_3️⃣ Download Required NLTK Data_

python -m nltk.downloader punkt averaged_perceptron_tagger maxent_ne_chunker words

_4️⃣ Run the Application_

python nlp_app.py

**🚀 Usage**

Launch the application by running nlp_app.py.

Use the GUI to register a new user or log in.

After login, you can perform the following NLP tasks:

Sentiment Analysis

Analyze the sentiment of any given text.

Named Entity Recognition

Extract entities such as people, places, and organizations.

Emotion Prediction

Detect emotional tone based on predefined emotion categories.

**🤝 Contributing**

Contributions are welcome.

If you would like to improve this project:

Fork the repository

Create a new branch

Submit a pull request

You can also open an issue if you find bugs or have suggestions.

**📄 License**

This project is licensed under the MIT License.
