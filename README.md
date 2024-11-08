# fake-news-detector
Here is one my NLP pet projects. It's purpose is to detect fake news written in English by either the title of an article or vy the it's text.

I've used only one ML model - SGDClassifier. Here are the scores:

  1) Perdiction by title:

     Accuracy on training data = 0.9920745729303548

     Accuracy on testing data = 0.9038497074222359

  2) Perdiction by text of the article:

     Accuracy on training data = 0.9998768068331143

     Accuracy on testing data = 0.9747459193101324

Libraries used: Pandas, NLTK, Joblib, and Scikit-learn.

The dataset on which models were trained: 
  1) Fake News Classification (https://www.kaggle.com/datasets/aadyasingh55/fake-news-classification)

P.S. You could use the code, but the training data isn't mine, so you'll have to look up the datasets' licences.
