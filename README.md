# Venture Funding with Deep Learning

You work as a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given you a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.


## Which binary classifier model is best to predict whether an applicant will become successful business.

Prepared by splitting my categorical and numerical data for a neural network model.
I used OneHotEncoder, train, test, split data, utilized Standard Scaler to standardize features.

Original model utilized two-layer deep neural network model, using relu activation function for both; output layer activation sigmoid.  

Alternative model 1 utilized - One layer deep neural network model, using tanh activation function; output layer activation softmax.  

Alternative model 2 utilized - One layer deep neural network model, using relu activation function; output layer activation linear.  Least accuracte and will not be considered.


The orginal model is the most accurate with precision:71%, recall: 81%, accuracy: 78%

Alternative model 1 is conflicting since precision: 53%, recall: 1%, and acuracy: 5%





---

Copyright 2022 2U. All Rights Reserved.
