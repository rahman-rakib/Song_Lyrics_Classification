# Song Lyrics Classification

![most frequent words in Eminem songs](https://spiced.space/ordinal-oregano/ds-course/_images/eminem_word_cloud.jpg)

## Overview
This project aims at building a text classification model on song lyrics. The task is to predict the artist from song text. Training such a model requires first of all that we collect our own lyrics dataset. We will focus on two artist from the "Heavy Metal" genre: Ronnie James Dio (Dio) and Ozzy Osbourne (Ozzy).

First, we will make use of the website:  http://www.darklyrics.com for collecting the dataset. Through webscraping we will download for each artist a HTML page with links to his albums, from whch we will extract album hyperlinks by HTML parsing. Then, we can again download HTML pages for all the albums, extracting song lyrics from each one of them.

Then, we train various models on the dataset we collected. We will select the best model hyperparameter tuning with k-fold cross validation. 

## Technology Stack
<img align="left" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">


