# NLP Homework - Module 12

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/toddshev/homework-NLP/main?filepath=https%3A%2F%2Fgithub.com%2Ftoddshev%2Fhomework-NLP%2Fblob%2Fmain%2FHomework%2FStarter_Code%2Fcrypto_sentiment.ipynb)

http://notebooks.gesis.org/binder/jupyter/user/toddshev-homework-nlp-kah0u4r5/tree/Homework/Starter_Code/crypto_sentiment.ipynb

#### The first section involved downloading Bitcoin and Ethereum articles, determining sentiment, and creating dataframes
* Ethereum had the highest sentiment analysis scores, though this may change based on the articles in the corpus

#### The next section involved tokenizing the text to be used in frequency analysis.
* The text was processed, including lemmatizing, punctuation removal via RegEx, and stopword removal.  
* These tokens were added to the dataframes for further analysis. 
* Single word counts and bi-grams were determined, and the most common were returned.

#### Then word clouds were created using the joined text from all articles for bitcoin and ethereum, respectively.

#### Lastly, Spacy was used for Named Entity Recognition.
* This technique involves determining the type of entity different words represent.  
* This includes, but is not limited to, people, organizations, dates, monetary units, cardinal values, etc.
