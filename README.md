<h1><b>Book Genre Classification Web App </b></h1>

<h3>Overview</h3>

This project is a Flask-based web application that classifies book summaries into different genres using a pre-trained machine learning model. The application processes user-provided text, applies text preprocessing techniques, and predicts the genre based on a trained model.

<h3>Features</h3

1.Cleans and preprocesses user-inputted text

2.Removes stopwords, applies lemmatization and stemming

3.Uses a trained TF-IDF vectorizer and machine learning model for classification

4.Displays the predicted genre on a simple web interface

<h3>Requirements</h3>

To run this project, install the required dependencies:
pip install flask nltk scikit-learn

Additionally, ensure that NLTK stopwords and WordNet data are downloaded:
import nltk
nltk.download('stopwords')
nltk.download('wordnet')

<h3>Model & Preprocessing Steps</h3>

Text Cleaning: Removes unnecessary characters and converts text to lowercase.

Stopword Removal: Removes common English stopwords.

Lemmatization: Converts words to their base form.

Stemming: Reduces words to their root form.

TF-IDF Vectorization: Converts text into numerical format.

Prediction: Uses a trained machine learning model to classify the text into one of six genres:
<ul>
<li>Fantasy</li>
<li>Science Fiction</li>
<li>Crime Fiction</li>
<li>Historical Novel</li>
<li>Horror</li>
<li>Thriller</li>
</ul>

<h3>License</h3>
This project is licensed under the MIT License.
