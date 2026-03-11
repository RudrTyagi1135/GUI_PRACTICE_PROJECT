**🧠 NLP App with Tkinter**

A GUI-based Natural Language Processing application built using Python and Tkinter.
The application allows users to perform multiple NLP tasks such as Sentiment Analysis, Named Entity Recognition (NER), and Emotion Prediction on user-provided text.

**✨ Features**
_🔐 User Authentication_

Register new users

Login with existing credentials

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
