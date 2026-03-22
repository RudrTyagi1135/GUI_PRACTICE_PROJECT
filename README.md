# 🧠 NLP App with Tkinter

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
- **User authentication system using JSON storage**
- **Interactive NLP tool design**

---

## 📂 Project Structure

```
GUI_PRACTICE_PROJECT/
│
├── App.py                # Main GUI application
├── mydb.py               # Database handling module
├── db.json               # JSON database storing users
├── requirements.txt      # Project dependencies
│
├── resources/            # GUI assets (images/icons)
├── About                 # About file for the project
│
├── .idea/                # IDE configuration files
├── LICENSE               # MIT License
└── README.md             # Project documentation
```

---

## ⚙️ Architecture Overview

The application follows a **simple modular architecture**.

```
User Interaction
       │
       ▼
Tkinter GUI
(App.py)
       │
       ▼
Application Logic
       │
       ▼
NLP Processing
(TextBlob / NLTK)
       │
       ▼
User Database
(db.json via mydb.py)
       │
       ▼
Results Displayed
on GUI Interface
```

### Design Principles

- **Separation of Concerns**
- **Reusable NLP modules**
- **Simple authentication architecture**
- **User-friendly desktop interface**

---

## 📊 NLP Functional Modules

### 💬 Sentiment Analysis

Uses **TextBlob** to evaluate sentiment properties such as:

- polarity
- subjectivity

Provides insight into whether text is **positive, negative, or neutral**.

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

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/your-username/gui-practice-project.git
cd gui-practice-project
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

Run the application:

```bash
python App.py
```

The **Tkinter GUI window** will open and allow users to interact with the NLP tools.

---

## 🧪 Example Workflow

1. **User registers or logs into the application**
2. User enters **text into the input field**
3. User selects an **NLP analysis tool**
4. The system processes text using **TextBlob or NLTK**
5. Results are displayed within the **GUI interface**

---

## 📈 Potential Improvements

Future enhancements could include:

- GUI redesign using **CustomTkinter**
- Deep learning NLP models
- SQLite database integration
- Export analysis results
- NLP visualization dashboard
- Packaging the application as a **desktop executable**

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

- **Desktop GUI development**
- **Natural Language Processing pipelines**
- **User authentication systems**
- **Python modular architecture**
- **Interactive NLP tools**

---

## 👤 Author

**Rudra Tyagi**

B.Tech Final Year Student  
**ML Systems / MLOps Engineer**
