# Hotel Rating Classification-Internship Project
In this project, our goal is to examine how travelers are communicating their positive and negative experiences in online platforms for staying in a specific hotel. Our major objective is what are the attributes that travelers are considering while selecting a hotel. With this manager can understand which elements of their hotel influence more in forming a positive review or improves hotel brand image.

# Datset
Dataset contains customer reivew and ratings to the perticular reviews.

# Requirements
* python
* pandas
* sklearn
* numpy
* nltk
* pickle(save model)

 Approach
We have approached for text preprocessing using nltk preprocessing method.
# Using NLTK(Natural language toolkit) library.
There are many libraries and algorithms used to deal with NLP-based problems. A regular expression(re) is mostly used library for text cleaning. NLTK(Natural language toolkit) and spacy are the next level library used for performing Natural language tasks like removing stopwords, named entity recognition, part of speech tagging, phrase matching, etc.

# Model Building
We have created the model like 
* LR algorithm gives 96 % accuracy.
* SVM algorithm gives  97% accuracy.
* NB algorithm gives 95%  accuracy.
* Random Forest algorithm gives 95% accuracy.
* Gradient Boost algorithm gives 96 % accuracy.
  
from above these we have selected SVM is the final model.Our model rendered accuracy of 97%, Saved this model using pickle.

# Deployment
To deploy this project run using streamlit

# https://nlpproject-aswgzdmjm7a3vjbz4ubksl.streamlit.app/

![image](https://github.com/Niro105/NLP_project/assets/126443419/84236ead-2bf7-41d7-8834-ac92d2bbfe91)

![image](https://github.com/Niro105/NLP_project/assets/126443419/2ca880b1-c1aa-4d5a-89a5-0c98f1fa1fdb)



