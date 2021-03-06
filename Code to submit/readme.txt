Step 1: Run the Preprocessing.py file. This generates an 'output.csv' file which will have the processed data.
Make sure the data file, 'cumulative_2020.09.04_15.26.41.csv' and the Preprocessing.py file are in the same folder.

Step 2: Run the corresponding file to run the classification algorithm on the 'output.csv'data.

To run Random Forest Classifier:
  1) download python and package prerequisites
  2) Make sure that the 'output.csv' file is in the same directory as RandomForest_withCV.py
  3) 'python3 RandomForest_withCV.py' should result in the confusion matrices and accuracy results.

To run Naive Baye's Classifier:
  1) download python and package prerequisites
  2) 'python3 NaiveBayesResults.py' should result in the resulting f1 scores, accuracy, and confusion matrix scores
  3) Make sure that the 'output.csv' file is in the same folder/the directory for loading in data is updated to the proper location with 'output.csv'

To run AdaBoost Classifier:
  1) download python and package prerequisites
  2) 'python3 adaboost.py' should result in the confusion matrices and accuracy results.
  3) Make sure that the 'output.csv' file is in the same folder/the directory for loading in data is updated to the proper location with 'output.csv'

To run Logistic Regression Classifier:
  1) download python and package prerequisites
  2) 'python3 logistic_regression.py' should result in the average accuracy and f1 scores as well as confusion matrix values
  3) make sure that 'output.csv' file is in the same folder as logistic_regression.py, and make sure you are running from that folder

To run Voting Classifier:
  1)'python3 VotingClassifier.py'

To run Neural Network Classifier:
  1) download python and package prerequisites, note that Keras and Tensorflow must be installed correctly
  2) Make sure that the 'output.csv' file is in the same directory as NeuralNetwork.py
  3) 'python3 NeuralNetwork.py' should result in the confusion matrices and accuracy results.
