# Text Analytics
Project of *Text Analytics* course, Data Science and Business Informatics - University of Pisa

A. Carnevale, G. Marcoccio, S. Telera

## Introduction
Philosophers and rhetoricians have been interested in irony and sarcasm for over 2500 years. In recent
times, they have been popular issues discussed; in this project will be taken an Irony and Sarcasm
detection on Tweets provided by an Evalita Challenge, called IronITA (Irony Detection in Italian
Tweets)

## Tasks
- Binary classification ironic / not ironic
- Multi Class Classification: not ironic / ironic but not categorized as sarcastic / sarcastic

![Immagine 2022-07-24 155829](https://user-images.githubusercontent.com/63819344/180650488-35f1c51e-42cd-4689-b787-b55a3cbc7138.png)
  
For the development of these tasks initially we have undertaken a Data Understanding analysis trying
to figure out our data, later through a Data Preprocessing we manipulated the raw text we had, in
order to obtain different types of it. Finally we did some analysis like distribution of words, using a
WordCloud to have a representative visualization.
Following, a classification analysis with simple classifiers has carried out (SVM, Naive Bayes and
Decision Tree) both binary and multi class and we have tried to improve the classification results
by integrating sentiment and emotions features. Finally, we developed LSTM and BERT to have an
exhaustive overview on the classification task with models specifically suited for NLP.

