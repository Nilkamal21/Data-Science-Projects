# News Classification Project

## Project Overview
This project aims to build a machine learning model for classifying news articles into predefined categories. It uses text data from various news sources and applies Natural Language Processing (NLP) techniques to preprocess the text, followed by a classification model to predict the category of each article.

## Project Structure
The project directory is organized as follows:

News Classification/ │ 
├── Data/ # Contains the training and testing datasets │ 
    ├── train.csv # Training data │ 
    └── test.csv # Test data │ 
├── Notebook/ # Contains the Jupyter notebook for the model │ 
    └── text_classification_with_logistic_regression.ipynb # The main notebook for model building and evaluation │  
└── Models/ # Contains the saved models and vectorizers 
    ├── logistic_regression_model.pkl # Saved logistic regression model
    └── tfidf_vectorizer.pkl # Saved TF-IDF vectorizer


## Requirements
To run this project, you'll need the following dependencies:

- Python 3.x
- scikit-learn
- pandas
- numpy
- joblib
- matplotlib
- seaborn

You can install these dependencies using the following command:

```bash
pip install -r requirements.txt


##Steps to Run the Model
    1.Clone the repository:

    git clone https://github.com/Nilkamal21/Data-Science-Portfolio.git
    cd Data-Science-Portfolio/News Classification
    
    2.Install the required dependencies:

    pip install -r requirements.txt

    3.Run the Jupyter notebook:

    jupyter notebook text_classification_with_logistic_regression.ipynb

    4.The model will train and evaluate on the provided data.


## License
This project is licensed under the MIT License

## Author
Nilkamal

##Contact
For any queries or suggestions, feel free to reach out to me:

GitHub: Nilkamal21
Email: nilkamaladhikari2005@gmail.com
