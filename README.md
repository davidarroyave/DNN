# DNN

Description of the German credit dataset.
Title: German Credit data

Source Information

Professor Dr. Hans Hofmann
Institut f"ur Statistik und "Okonometrie
Universit"at Hamburg
FB Wirtschaftswissenschaften
Von-Melle-Park 5
2000 Hamburg 13

Number of Instances: 1000

Two datasets are provided. the original dataset, in the form provided by Prof. Hofmann, contains categorical/symbolic attributes and is in the file "german.data".

For algorithms that need numerical attributes, Strathclyde University produced the file "german.data-numeric". This file has been edited and several indicator variables added to make it suitable for algorithms which cannot cope with categorical variables. Several attributes that are ordered categorical (such as attribute 17) have been coded as integer. This was the form used by StatLog.

Number of Attributes german: 20 (7 numerical, 13 categorical) Number of Attributes german.numer: 24 (24 numerical)

For this scenario, it was selected the numerical dataset because the data is already in int64 format, making it suitable for classification tasks without further preprocessing.

The dataset link is currently in the jupyter file description. To work with it, it was converted to csv.
