# NLP_Real_Disaster_or_not
A very interesting Natural Language Processing project that determines whether or not a tweet is actually one that describes a real disaster or not.
The dataset consists of the following:
  1. ID
  2. Text of the tweet
  3. Location
  4. Keyword
  5. Target
An important part of this project is Data Cleaning, in order to get it ready for our model. But first, take a look at what our data really looks like. For this we perform some Exploratory Data Analysis and get an idea of our classes. for instance, we check how many words are in tweets that describe what a real disaster looks like, and tweets that don't. We also create a corpus of stopwords as they don't really add much meaning. Another interesting analysis performed is the bigram analysis that checks which two words are found often in each of the classes. Other data cleaning involves removing punctuations, html tages, URLs, and emojis. Additionally we create word clouds for words found in each class to easily visualize the most frequently occuring words in each of the classes.
We then create a Bag of Words to pr-process the data before modelling.
After This, we use Latent Semantic Analysis to help determine relationships between unstructured data such as words. 
Finally, we use Term Frequency - Inverse Document Frequency to determine the importance of a word in each class.
We then create a classification model using GloVe (Global Vectors of Word Representation).
