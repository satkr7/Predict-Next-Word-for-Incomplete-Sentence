# Next Word Prediction for a Incomplete Sentence

## Input / Output
* Input senctence must be of lenght 3
* Output will be most probable predicted next word
* Output is list of 5 words which are most likely to be next word, 1st word being the best probabilty and so on.
* Probabilities of each of 5 words are also printed


##  Output Overview
![alt text](https://i.imgur.com/kC1WpJG.png)
![alt text](https://i.imgur.com/HWsPO88.png)

## Libraries:
- pandas
- keras
- dlib
- pickle
- sklearn
- json
- re
- numpy
- os

## Usage:
1) Download ipynb notebook and run
2) Import necessary packages
3) Load saved keras model : "model.h5" and "model.json"
4) Load dictionary file having word:id pairing : "word_to_id.json"
5) Run Testing code
6) For every 3 words input sentence , predict 1 next word

## Author:
> SATYAM KUMAR
