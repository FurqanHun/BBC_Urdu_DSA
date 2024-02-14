# BBC News Urdu DSA

## Description
This is a project for the Data Structures and Algorithms course at the Sindh Madressatul Islam University. The project uses python to scrape data from the [BBC News Urdu](https://www.bbc.com/urdu) website and store it in a database. The title or headline of the news from the data is taken as x and topic of the headline as type is then used to train four different machine learning models i.e. Logistic Regression, Decision Tree, Random Forest, Support Vector Machine using four different counting techinques i.e. TF-IDF, Hash Matrix, Count Vectorizer, and n-grams.

Aside form four different machine learning models, the project also uses a deep learning model i.e. Long Short Term Memory (LSTM) to train the data. The LSTM model is trained using the headline or title from the data and the topic and of the news as y. The model is then used to predict the topic of an news based on the headline or title.

## Disclaimer
This project is for educational purposes only and is not intended for commercial use. The project is not affiliated with the BBC News Urdu website in any way.

## Special Thanks To
- [BBC News Urdu](https://www.bbc.com/urdu) for providing the data.
- [Danyal Saeed Mirza](https://github.com/Delta-Sigma) for providing urdu stop words.

Checkout and contribuite to the Urdu Stopwords repository [here](https://github.com/Delta-Sigma/urdu-stopwords).