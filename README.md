# Handwritten Letter Language Classifier
Introduction to Artificial Neural Networks (CS539 UW-Madison)

## Authors 
Caleb Federman, Connor Braun, Elias Cassis, Tate Waugh

## Overview
Our objective is to develop a machine learning framework adept at recognizing and classifying characters from diverse alphabets, subsequently identifying the associated language. By employing a convolutional neural network, the system will be trained on a comprehensive dataset of written characters, striving for proficient classification that can accurately discern the alphabet and language. Furthermore, the framework will encompass a component capable of analyzing words, where it leverages the certainty levels of individual character classifications, along with contextual cues like word length and dictionary references, to ascertain the language, and thus the individual characters, of the entire word.

## To Run:
All files are written for google colab, and thus must be run in google colab with this folder in your root drive. Change where the data is loaded from in google drive if using a different path, or to local files if not running on colab.

Processed files are uploaded. To recreate, run the relevent Load*Language*Data.ipynb.

To see results run CNN.ipynb.

It is recommend to run on a GPU to decrease compute times.

### Datasets
<a href="https://www.kaggle.com/datasets/mohneesh7/english-alphabets">English Handwritten Alphabet</a><br>

[Arabic Handritten Alphabet](https://www.kaggle.com/datasets/insafbenlamari/arabic-letters)

<a href="https://www.kaggle.com/datasets/tatianasnwrt/russian-handwritten-letters">Russian Handwritten Alphabet</a><br>
