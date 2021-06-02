# Reddit_Flair_Classification
#### Objective
There is a dataset consisting of Reddit posts consisting of their content, title, author, and flair taken from a particular subreddit. a multi-class classification task  that considers the provided data to detect the flair that should be assigned to a particular post.

#### Dataset
https://github.com/SforAiDl/Summer-Induction-Assignment-2020/tree/master/Question%204.2/NLP%20Data/data

This project requires Python 3 and the following frameworks and libraries:

* sklearn
* TensorFlow & Keras
* NLTK
* pandas
* Numpy
* Matplotlib

#### Classification
* There are 15 labels (Flair)
1. Data exploration and Baseline implementations 

 ![image](https://user-images.githubusercontent.com/56354373/120467875-3b3d2e80-c3be-11eb-8cb5-0733995db292.png)

validation accuracy - 46.36

2. Implementing Bi-LSTM with attention layer and GloVe embedding to represent tokenized words
![image](https://user-images.githubusercontent.com/56354373/120465297-725e1080-c3bb-11eb-852d-1ab1891ed49a.png)

 validation accuracy - 52.33
