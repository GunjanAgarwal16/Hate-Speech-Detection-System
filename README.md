# Hate Speech Detection System

This repository contains the source code and documentation for the Hate Speech Detection System project, developed as a part of the Bachelor of Engineering degree requirements. The project leverages machine learning techniques to identify and classify instances of hate speech within textual data, with the ultimate goal of contributing to the creation of safer online environments.

## Project Overview

The proliferation of social media platforms has led to an increase in hate speech, which poses significant threats to online communities. This project addresses this issue by implementing a machine learning model, specifically Logistic Regression, to detect hate speech. The model is trained on a dataset of tweets, preprocessed to remove unnecessary elements, and evaluated using various performance metrics.

## Features

- **Data Preprocessing:** Removal of Twitter handles, special characters, numbers, punctuations, and short words. Stemming is applied to standardize the words.
- **Feature Extraction:** Uses CountVectorizer to convert textual data into a bag-of-words representation.
- **Model Training:** Logistic Regression is used to classify text as hate speech or non-hate speech.
- **Model Evaluation:** Performance is evaluated using F1 score and accuracy metrics.
- **Deployment:** The model is deployed in a Streamlit application for real-time detection of hate speech.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK, Streamlit
- **Machine Learning Model:** Logistic Regression
- **NLP Techniques:** Stemming, Tokenization, CountVectorizer

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/hate-speech-detection.git

2. **Navigate to the repository:**
   ```bash
   cd hate-speech-detection

3. **Install the required Python packages:**
   ```bash
   pip install -r requirements.txt

4. **Run the streamlit application:**
     ```bash
   streamlit run app.py
  
## Usage
- The application allows users to input text and receive a classification as either hate speech or non-hate speech. The model uses a probability threshold to determine the classification, which can be adjusted for better precision.

## Project Structure
- train.csv: The dataset used for training the model.
- app.py: The Streamlit application for real-time hate speech detection.
- hate_speech_detection.ipynb: The Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- README.md: Project documentation.
-requirements.txt: List of dependencies required to run the project.

## Acknowledgments
We would like to express our sincere gratitude to our project guide, Dr. Nazneen Pendhari, for her valuable guidance and support throughout this project. We also extend our thanks to the faculty and staff of the Computer Engineering department at M.H. Saboo Siddik College of Engineering for providing the necessary resources and environment to successfully complete this project.

## Contact
For any inquiries or further information, please contact:
Agarwal Gunjan Hemant
Email: gunj16102002@gmail.com
   

   



   

   
