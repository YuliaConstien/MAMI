# Multimedia Automatic Misogyny Identification


This is a GitHub repository for the final semester project in the Advanced Natural Language Processing course, in the master of Cognitive Systems programme of Potsdam University.

This project is based on the SemEval2022 Competition Task 5:Basic Multimedia Automatic Misogyny Identification, Subtask A: a basic task about misogynous meme identification, where a meme should be categorized either as misogynous or not misogynous.

In this repository we included three models:

- Convolutional neural network model for the binary classification of the memes images. 
- Neural network model for the classification of the embedded memes text. 
- Fused version of te two models predictions for the final classification of memes as whole.

All three files were created in Google Colaboratory, and thus need a notebook enviroment to be run.

The repository includes a dataset file, where one can find instructions for the request of the dataset from the official SemEval22 repository. After applying the right paths for the datasets the two baseline models should be run first. This will create a pickle file of the predicted labels for each model. Once both pickle files are created it is possible to run the fusion, which uses these two files as input.

The fusion file also includes the evaluation of the three models.




