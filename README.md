# spamclassification

{`Text classifier’ to classify ‘SMS spam classification’}.
 The problem statement is basically about creating a 'spam', and 'ham' classification NLP model and the dataset is "spam.csv" from Kaggle.

 We will consider class and message w.r.t Dataset, based on the particular message we will try to train our model, if this is 'spam' or 'ham'.

 Flask framework is used to do the deployment part.

 Splitted the train and test data, and then implemented a multinomialNB algorithm, The Multinomial Naive Bayes algorithm is a Bayesian learning approach popular in Natural Language Processing (NLP). The program guesses the tag of a text, such as an email, using the Bayes theorem. It calculates each tag's likelihood for a given sample and outputs the tag with the greatest chance. 

 Using the pickle library function the trained model will be stored in a .pkl file named, nlpmodel.pkl. 

 After the .pkl file is generated, the training code will be commented on.

 Using the conda the code is deployed into the web. ~\textbf{"python app.py"}
