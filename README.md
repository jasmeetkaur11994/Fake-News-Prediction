# Fake News Detection using Passive Aggressive Classifier
This project focuses on developing a machine learning model that can predict the authenticity of news articles using the Passive Aggressive Classifier algorithm. The model is trained on a dataset of labeled news articles and deployed using Flask, a web development framework for Python. The Flask application allows users to input news articles and get predictions on whether they are real or fake.

#### Dataset
The dataset used in this project is a collection of labeled news articles obtained from the Fake News Challenge dataset. The dataset contains news articles labeled as either "real" or "fake". The training set consists of 31,863 articles, and the testing set consists of 6,358 articles.

#### Methodology
The project involves pre-processing and feature engineering of text data, as well as training and evaluation of the machine learning model. The pre-processing steps include tokenization, stop-word removal, and stemming to clean and transform the raw text data. Feature engineering techniques such as term frequency-inverse document frequency (TF-IDF) are used to represent the text data in a numerical format for machine learning algorithms.

The machine learning model used in this project is the Passive Aggressive Classifier algorithm, which is a linear classification algorithm that is commonly used in text classification tasks. The model is trained on the pre-processed and feature-engineered dataset to predict the authenticity of news articles.

The Flask web application allows users to input a news article, which is then pre-processed and passed through the trained machine learning model to predict whether it is real or fake. The final product combines natural language processing, machine learning, and web development techniques to create a user-friendly and practical tool for identifying fake news.

#### Requirements
1. Python 3.6 or higher
2. Flask
3. Scikit-learn
4. Pandas
5. NumPy

#### How to run the application
Clone the repository to your local machine.
Install the required packages using pip install -r requirements.txt.
Run the Flask application using python app.py.
Open the web application in your web browser at http://localhost:5000.

#### Conclusion
Fake news is a serious problem that can have significant consequences. This project shows how natural language processing and machine learning techniques can be used to identify fake news articles. The Passive Aggressive Classifier algorithm provides a practical solution for text classification tasks, and the Flask web application makes the final product user-friendly and accessible.
