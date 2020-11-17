# NLP
Naive Bayes on a Text Classification Task


# Intoduction 
There are different types of data that we can process and build models based on them. These types of data have different properties. We can distinguish continuous signs that describe the number, and categorical signs, which are elements of a fixed list. There is also a third type of signs that can be found in various fields - text. For example, when classifying e-mail messages as spam and really necessary letters, the text of the letter itself will certainly contain important information for this classification task. Text data is usually represented as strings of characters. The text-based data analysis technique in machine learning is called NLP. (Badreesh S., 2018).

# Naive Bayes method
Overview: For this project, we will be using Naïve Bayes to classify the sentence. Sentence should be Inspiring or Dull. To do this, we will build Naïve Bayes classifier on feature vectors. . One of the simplest, but most effective and widely used way to prepare text for machine learning is to represent text information in the form of a "bag of words". Using this representation, we remove the structure of the source text, for example, chapters, paragraphs, sentences, formatting, and only count the frequency of occurrence of each word in each document in the corpus. For each word recorded in the dictionary, we calculate the frequency of its occurrence in each document. This means that in our numerical representation, each feature corresponds to each unique word in the dataset. Feature vectors we get by using the CountVectorizer function When constructing, the Naive Bayesian Algorithm is based on Bayes' Theorem which works on the theory of probability. Bayes' Theorem implies that you can calculate the probability of an event assuming that another event has occurred interdependent with it. For example, a berry can be considered a watermelon if it is green and large in size.
The main advantages of a naive Bayesian classifier are ease of implementation and low computational costs for training and classification (Jaya A., 2019).

Data: The dataset consists of 6 different sentences which are labeled as Inspiring or Dull (Figure 1).

# Python 3 code:
1. First, let's load the required libraries

2. Let's create a structure for the text data that we have as a training date set. To do this, let's build a data frame from two columns "Sentence", "Class".


3. Divide the date frame into feature and labels.


4. Let's load the text we need to classify and create feature vectors.


5. Сompiles the Naive Bayes algorithm and display the result.


# Conclusion: Our algorithm predicted that this is an Inspiring test sentence.
