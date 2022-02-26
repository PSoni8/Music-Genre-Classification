# Music-Genre-Classification
### Introduction
It is a machine learning model to automatically classify different musical genres from audio files.
### About
Our project is a research – based analysis of the music genres using spectral and rhythmic features of the music We have done a comparative study using various machine learning algorithms to classify the music into its various genres namely, blues, classical, country, disco, hip-hop, jazz, metal and pop respectively. We have used various audio features, such as Mel Frequency Cepstral Coefficients (MFCC), Delta, Delta- Delta and temporal features, including beats and tempo to featurize our data. Various classification algorithms, such as Support Vector Machine(SVM), Decision Tree, k-Nearest Neighbors(KNN), Random Forest and Gradient Boosting Classifier are used in the classification of the data.
### Dataset
Contains 1000 music files. Dataset has ten types of genres with uniform distribution. Dataset has the following genres: blues, classical, country, disco, hiphop, jazz, reggae, rock, metal, and pop. Each music file is 30 seconds long.</br>
Genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds.</br>
Images original - A visual representation for each audio file. One way to classify data is through neural networks. Because NNs (like CNN, what we will be using today) usually take in some sort of image representation, the audio files were converted to Mel Spectrograms to make this possible. </br>
The files were collected in 2000-2001 from a variety of sources including personal CDs, radio, microphone recordings, in order to represent a variety of recording conditions.</br>
https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification
### Workflow
1.Preprocess the data using FFT (to convert original data into frequency domain).</br>
2.Feature Extraction using MFCC, Delta, Delta- Delta and rhythmical features.</br>
3.Feature Reduction using Principal Component Analysis.</br>
4.Optimisation of hyper-parameters using Grid Search with Cross-Validation.</br>
5.Training the classifier using various classification algorithms.</br>
6.Testing the data and predicting  the genre of our data files.</br>
7.Compare performances of different classifiers using different benchmarks.
### Technology Used
Python</br>
ML Algorithms</br>
Sklearn</br>
Matplotlib</br>
Numpy & pandas</br>
Scipy</br>
Librosa</br>
python_speech_features
### Use cases
Genre classification can be of great utility to musical information retrieval systems.</br>
Genre is intrinsically built on the similarities between pieces of the same genre and differences between pieces of different genres.</br>
An automated genre recognition system would make it possible to classify and search large electronic music libraries.</br>
In order to generate better recommendation, user generated rating & reviews, genre or books metadata is used.</br>
