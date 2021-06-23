# NLP-PROJECT :  SMS-SPAM-Detection

## PURPOSE:

Everyday, we receive a lot of messages from different sources, and some of those messages might be coming from an advertisement machine. Due to such messages,
mobile users get irritated and may even ignore real messages from friends. In order to prevent this, we will categorize these SMS messages into two categories: SPAM and HAM.

## For Visualization – Adding new column:
In order to visualize our dataset, we need to add one column which shows the total number of words.

## Text Pre-processing:
 ### Punctuation:
 import string library to remove punctuation.
 ### Stopwords:
  import string library to remove stopwords in english.
add all these in one function called text_process , this function will remove punctuation and stopwords.

## Vectorization:
   CountVectorizer : We can use CountVectorizer to count the number of times a word occurs in a corpus.
   
## TfidfTransformer:
  TfidfTransformer:We can use TfidfTransformer to count the number of times a word occurs in a corpus (only the term frequency and not the inverse), also is  normalizing the count.
  
  
## Split the dataset into train and test:
we are going to split the dataset into train and test. The test dataset is used for validating our models.

## choose the model the naive classyfier :
Let’s start training our models. The  model we are going to use is Naïve Bayes.

## Create a Pipeline:
Create a pipeline containing CountVectorizer(), TfidfTransformer(), MultinomialNB() togather

## Evalution:
import classification_report , confusion_matrix to see the accuracy and f1-score 
