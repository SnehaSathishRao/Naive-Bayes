# Naive-Bayes
**About Algorithm:**<br />
Naive Bayes is a simple, yet effective and commonly-used, supervised machine learning classifier.It is a probabilistic classifier that makes classifications using the Maximum A Posteriori decision rule in a Bayesian setting. It can also be represented using a very simple Bayesian network.This algorithm is parameteric,which implies that there is an assumption.This algorith is named so because it is so naive that it treats all its fetures to be independent.This is popularly used in Sentimental analysis(text based classifications).<br />
**Data:**<br />
I have used Amazon data which contains summary of reviews that is featurized using NLP techniques(Bag of words,TfIdf) gives higher dimensional.The Amazon data that is been used has already been pre-processed and loaded.<br />
**Summary:** <br />

 | Model  | Hyper_parameter(K) |   Train f1-score   |   Test f1-score    | 
 | ------------- | ------------- |------------- | ------------- |
 |  BOW   |         1          | 0.9448527014818333 | 0.9439662194303438 |
 | TF_IDF |        0.01        | 0.9445729338750725 | 0.9441151460584233 |
