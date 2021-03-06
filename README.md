# Deeplearning Scratchpad with Keras

The purpose of this repo is to demonstrate a few toy projects for ideas in deep-learning, particularly using the [keras](https://keras.io/) framework.

Most of this is stuff that I have learnt while doing the [google course on deeplearning on udacity](https://eu.udacity.com/course/deep-learning--ud730) as well as a various other blogs and youtube videos.

The core of the repo consits of a few notebooks. notebooks/index.ipynb is the main entry point to the repo, from there everything should link to further notebooks and be self explanatory.

## Key models

There are three key things that I do here:

* Convolutional Neural Network: In which I train the data on pictures of animals or famous people, which I get from the web using the bing API. The user can ask for any two or more categories and the API will go to Bing images and download many pictures of each of these classes. The model will then classify these images as one of these categories.

* Word2Vec algorithms: I take the complete works of shakespeare and look at the words that are found in shakespeare, and embed them in a lower dimentional space, and illustrate the relationships between words in this space. 

* RNNs: Uses the LSTM model to generate some fake shakespeare. Can be configured to work with any corpus of text such as the bible or any other source.