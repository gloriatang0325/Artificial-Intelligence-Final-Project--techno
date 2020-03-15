# Artificial-Intelligence-Final-Project--techno

Welcome to my final project for CSE 573 Artificial Intelligence!

The topic is Techno Music Classification.

Techno is a genre of electronic dance music that is characterized by a repetitive four on the floor beat which is generally produced for use in a continuous DJ set. 
There are six main sub-genres of techno music, which are Acid Techno, Ambient Techno, Detroit Techno, Industrial Techno, Minimal Techno and Tech House.

*Methodology I*

Transfer Learning with pre-trained model musicnn and linear classifier SVM and DNN
You can find the code in Transfer Learning.ipynb and DNN.ipynb.
Transfer Learning.ipynb aimes to extract the penultimate neurons of the pretrained model musicnn(freeze all other layers) and get the output as our input for the linear classifiers.
DNN.ipynb aimes to do the linear classification with SVM and DNN.


*Methodology II*

Feature Engineering from audio spectrogram with extracted 27 features.
You can find the code in Feature Engineering.ipynb.
Algorithms such as random forests, support vector machines and extreme gradient boosting are used.


*musicnn
https://github.com/jordipons/musicnn
