
# Project: Medical Chatbot - Symbot (NLP)

This project implements a medical chatbot based on Natural Language Processing (NLP) to provide automated responses to user queries regarding medical symptoms. The model uses advanced machine learning techniques to understand and respond to queries, offering intelligent and helpful interaction in the healthcare domain.

## Description

This project uses a machine learning model to create a chatbot capable of answering health-related questions. The algorithm is designed to recognize symptoms mentioned by the user and offer advice or recommendations based on medical data.

### Features:

- **Natural Language Processing (NLP)**: Utilizes NLP algorithms to understand user queries.
- **Automated Responses**: Generates accurate answers based on medical symptom queries.
- **Supervised Learning**: The model is trained using a dataset of medical questions and answers.
- **Simple and Efficient Interface**: The chatbot can be integrated into a user interface (e.g., website, mobile app).

## Prerequisites

Before running this project, you must install the following dependencies:

- Python 3.x
- Librairies required : Flask, PyTorch
, NLTK
, NumPy
, Scikit-learn
, Pandas
, matplotlib

## Install requirements

Before running the application you need to install the dependencies. We recommend to use the virtual environment
[virtualenv](https://pypi.org/project/virtualenv/) for this.

Linux:

```
python3 -m venv venv
venv/bin/activate
pip install flask torch nltk numpy sklearn pandas matplotlib
```
Windows:

```
python -m venv venv
venv\Scripts\activate
pip install flask torch nltk numpy==1.19.3 sklearn pandas matplotlib
```

This will install all the required dependencies needed to run the application successfully.

## Run

To run MedicalChatbot, `cd` into MedicalChatbot repo on your computer and run `python -m flask run`. This will run the Flask 
server in development mode on localhost, port 5000.

`* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)`
