# Fake-News-Detection
# A python model which can predict the given news is fake or real.

What is this project about? 
It is a python model built in jupyter which predcit the given NEWS is fake or real.
Now the question arises what is Fake News and how do we identify it ?

So, Fake News term is used for the fabricated news. It is created to deceiving people. It a lie created out of nothing – that takes the appearance of real news.
It is a type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often 
done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being 
viralized by algorithms, and users may end up in a filter bubble.


Terms used in the model, please go through it before implementing.
What is a TfidfVectorizer?
TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document 
is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant 
a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

What is a PassiveAggressiveClassifier?
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of 
a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change
in the norm of the weight vector.

