# assignment-solutions
steps done for nlp:
1)imported libraries
2)imported dataset
3)used text preprocessing such as 
  a) converting every letter from capital to small 
  b) removing , 
  c) spltting the sentence to words
  d) lemmatizing
  e) joining them
  f) appended in corpus
 4) convert corpus to array format
 5) converted medicine column from categorical to numerical 
 6) merged the two columns
 7) splitted train data to train and test set
 8) applied different model such as
  a) naive bayes
  b) logistic regression
  c) random forest
  d) XG Boost Classifier 
 9) model evaluation metric is accuracy i.e  XG Boost Classifier was highest with 75%
 10) applied the model on test data after preprocessing and saved as csv file
 
 
steps thinking to approach computer vision:
1) reading data Csv file 
2)writing loop for for csv labels to read images
3)preprocessing images
  a)rotating images
  b)shear range 
  c)zoom range
  d)scaling
 4)then building algorithm 
 5)try ingdifferent number of layers of convolution and maxpooling 
 6) adding dense layers 
 7)if overfitting occurs then adding dropout layer
 8)final output layer 
 9)testing the model if accuracy doesnt increase gradually then use different architecture such as vgg19, vgg16, resnet etc.
 10)then again testing and finalising the model 
 
