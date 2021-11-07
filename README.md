# Fake-News-Detection

In this we are using Political News Dataset and classifying them whether the news is real or fake.

Dataset - The shape of the Dataset is 7796×4. It contains the following attributes :-

1) Title of the News Article
2) Text
3) Fake/Real

Algorithms Used - TF-IDF Vectorizer and Passive Agressive Classifier

* TF-IDF(Term Frequency- Inverse Document Frequency) Vectorizer  - This is used to convert the text into vector of words. It reflects the importance of a word in the document for classification.

* Passive Agressive Classifier - It is an Online Learning Algorithm, where a tuple of data is used only once and then discarded. The reason for choosing this algorithm is that when we have very large amount of data (Exp-in Tb), it is difficult to use the same instance again and again in multiple iteration as it is very computationally  expensive.

Application Areas :-
1) Twitter where more than 500Gb of Data is produced everywhere
2) Google
