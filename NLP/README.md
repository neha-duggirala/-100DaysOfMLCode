# Natural Language Processing 
 ## 100 Days of ML Coding Challenge Log 💥
 Deep learning always fascinates me:smiley: Wanted to challenge myself again by starting 100DaysOfMLCode for the second time. This time I wish to dive deeper into the topics like NLP, computer vision. By the end, I hope to do really cool projects and contributions to the ML community
 
## Day 1 | Text Preprocessing 
Unlike in computer vision where we fed the DNN the pixel values, in NLP it's not possible to feed words or letters to the DNN. For the DNNs to learn about the corpus, some text preprocessing tasks are to be performed. So these are the topics I have learned
1. Tokenization
2.  Word Index
3. Text sequence
4. Padding  

## Day 2
Implemented text preprocessing on a real dataset for sarcasm detection. Check the [code](https://github.com/neha-duggirala/100DaysOfMLCode/blob/master/NLP/Sarcasm_detection.ipynb)  here. You can find the [Dataset📚](https://rishabhmisra.github.io/publications/)

## Day 3 | ML Project
Started working on Bosch Production Line dataset from Kaggle. It has 970 features, 1183747 records and data cleaning has to be performed.
Link to the [Dataset](https://www.kaggle.com/c/bosch-production-line-performance/overview)

## Day 4 | Word Embeddings
The idea that words and associated words are clustered as vectors in a multi-dimensional space is called Word Embedding.

## Day 5,6,7 | Projects
There various topics I have covered.
### Tensors
[Tensors](https://www.tensorflow.org/guide/tensor) are multi-dimensional arrays with a uniform type. They are immutable( cannot be changed) There are scalars, 1d, 2d and soon. A 4d tensor of shape (3,2,4,5) can be visualized as follows<br>
<img src='https://www.tensorflow.org/guide/images/tensor/4-axis_block.png' width=250 height=250/>
<img src='https://www.tensorflow.org/guide/images/tensor/shape2.png' width=250 height=250/>

### How to use weights and bias
[Tutorials](https://app.wandb.ai)

### Global avg pooling vs flattening

## Day 8,9 | Theory

Watched a [playlist](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=2&t=878s) about word vectors and origin of NLP

## Day 10,11 | Word2Vec
Understood the math for likelihood, cost function, prediction function and similarity between the center word vector and other word vector. This is very interesting [Video](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=1)
<img src="https://adriancolyer.files.wordpress.com/2016/04/word2vec-king-queen-composition.png?w=656"/><br>
[Word2Vec Explained!](https://www.youtube.com/watch?v=yFFp9RYpOb0) is one good resource.

## Day 12,13 | IMDB Review
Worked on training a model to analyse sentiment of a movie review with the dataset. Check out the code [here](https://github.com/neha-duggirala/IMDB-review-classification)

## Day 14,15 | Data Visualization
Learned different visualization tools
1. Matplotlib
2. Plotly
3. Seaborn

## Day 16,17 | Widhya
Worked on creating a mission for a platform for [Widhya](https://widhya.org/#/). There was a dataset which has a list of colleges and the ratings of technologies each college is good at. Worked on visualization of data using Matplotlib and Plotly. Had fun creating modules!  
4. bokeh 

## Day 18, 19 | Stcok market prediction using Linear regression
Worked on quandl stock dataset. I have observed that linear regression gives a best fit line that other algorithms like SVM. Also understood a few concepts of stock market. 

## Day 20,21,22,23 | Generation of Poetry
[Code](https://github.com/neha-duggirala/Poetry-Generation) to the project

## Day 24,25 | RNNs
From the following resources, Understood the working of RNNs
1. [Python programming](https://pythonprogramming.net/recurrent-neural-network-rnn-lstm-machine-learning-tutorial/)
2. [Recurrent Neural Networks - Ep. 9 (Deep Learning SIMPLIFIED)](https://www.youtube.com/watch?v=_aCuOwF1ZjU)
3. [ML with Recurrent Neural Networks (NLP Zero to Hero - Part 4)](https://www.youtube.com/watch?v=OuYtk9Ymut4&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S&index=4)
4. [Illustrated Guide to LSTM's and GRU's: A step by step explanation](https://www.youtube.com/watch?time_continue=220&v=8HyCNIVRbSU&feature=emb_title)

## Day 26 | NLP deeplearning.ai certification
Over the last four weeks, I have learnt
1. Basic Tokenization and Padding of text .
2. Embeddings, and how words could be mapped to vectors, and words of similar semantics.
3. Sequence models.<br>
Wrapped up by taking everything I learned and using it to build a [poetry generator!](https://github.com/neha-duggirala/Poetry-Generation)
This is just a beginning in using TensorFlow for natural language processing. Hope to dive deeper 🏊‍♀️

## Day 27,28,29,30 | Logistic regression for sentiment analysis
1. Natural Language preprocessing using nltk <br>
 a. Tokenizing the string<br>
 b. Lowercasing<br>
 c. Removing stop words and punctuation <br>
 d. Stemming <br>
 ```
from nltk.corpus import stopwords          # module for stop words that come with NLTK
from nltk.stem import PorterStemmer        # module for stemming
from nltk.tokenize import TweetTokenizer   # module for tokenizing strings
```
2. Visualizing word frequencies <br>
3. Visualizing tweets and Logistic Regression models <br>

## Day 28,29 | [Challenge](https://datahack.analyticsvidhya.com/contest/linguipedia-codefest-natural-language-processing-1/#ProblemStatement)

Using [pandas-profiling](https://www.linkedin.com/feed/update/urn:li:activity:6680821087158194176/) is of great use. This removed the burden for usage of applying info, unique, isna and what not just to get insights from of data. <br>

## Day 30 | Natural Language Processing with Deep Learning in Python Course in Udemy

After 10 months, I decided to take up a course on NLP apart from my profesional work(which includes only using pandas, a few python logics, excel and SQL). 
