# Multimedia Autimatic Misogy Identification


This is a GitHub repository for the final semester project in the course Advanced Natural Language Processing, in the Master of Cognitive Systems:Languge,Reasoning and Learning of the Potsdam University in Germany.

This project is based on the SemEval2022 Competition Task 5:Basic Multimedia Automatic Misogyny Identification, Subtask A: A basic task about misogynous meme identification, where a meme should be categorized either as misogynous or not misogynous.

In this task we introduce as a first step two baseline models. A Cnn (Convolutional Neural Network) for the binary classification of the meme images and a simple Nn (Neural Network) for the classification of the embedded meme text. Then we fuse the predictions of the two models for the final classification of memes as a whole.

In the repository in the file Dataset one can find instructions for the request of the Dataset from the official SemEval22 repository. Then after carefully applying the right paths for the files one needs to run first one of the two baseline models. This will create a pickle file of the predicted labels. After that the second baseline model needs to be ran as well in order for the second pickle file to be created. Once both pickle files are created one can to run the fusion, which uses these two files as an input.

In the fusion file one can also find the evaluation of the three models.


