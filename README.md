# SMS Text Classification Project

This project classifies SMS messages, likely between categories such as "spam" and "ham" (not spam), using various machine learning techniques. The notebook is structured to clean, preprocess, and classify SMS messages from a dataset, utilizing popular machine learning and natural language processing (NLP) techniques.

Project Overview
The notebook loads SMS data, preprocesses the text, and builds a machine learning model to classify SMS messages accurately. Key steps include:

### Data Loading:
Importing training and validation datasets.
### Data Preprocessing: 
Cleaning text data and transforming labels.
### Feature Extraction:
Using TF-IDF vectorization to represent text numerically.
### Model Building and Training:
Training classification models (e.g., Random Forest and Logistic Regression).
### Hyperparameter Tuning:
Fine-tuning the model using grid search.
### Evaluation:
Measuring the model's accuracy on validation data.
Requirements
The following libraries are required to run the notebook:

pandas
numpy
scikit-learn
Install them using:

pip install pandas numpy  scikit-learn

## Project Structure
Data Loading: The data is loaded from .tsv files hosted on a remote server.
Data Preprocessing:
Label encoding is applied to transform categorical labels.
Text is cleaned using regular expressions to remove unwanted characters.
Feature Extraction: TF-IDF vectorization converts the text data into numerical features for model training.
Modeling:
Random Forest and Logistic Regression classifiers are used.
Hyperparameter tuning via GridSearchCV enhances model performance.
Evaluation:
The model’s accuracy is computed to assess classification quality.
 
## Results
The notebook evaluates the classification accuracy and can serve as a foundation for further improvements or additional experimentation with other classifiers or NLP techniques.
