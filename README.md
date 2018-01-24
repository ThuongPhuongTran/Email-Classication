# Email-Classication
Classify spam or non-spam email
In the UCI data repository, choose the Spambase dataset and
solve the problem of classifying email as spam or non-spam using machine learning
models. Here, download the material from the following web page:
http://archive.ics.uci.edu/ml/datasets/Spambase

The functional structure of the input features and machine learning models for spam email data classification
1.	The functional structure of the input features
The data consists of 4061 number of instances with 1812 spam emails ~39.4%.
Attribute Information: the lass column of data is label to consider the email spam (1) or not (0). Data [55-57] in array measure the length of sequences of consecutive capital letters. 
-	48 continuous real [0,100] attributes of type word_freq_WORD which is percentage of words in the e-mail that match WORD list.
-	6 continuous real [0,100] attributes of type char_freq_CHAR which is percentage of characters in the email that match CHAR
-	1 continuous real [1,...] attribute of type capital_run_length_average = average length of uninterrupted sequences of capital letters
-	1 continuous integer [1,...] attribute of type capital_run_length_longest = length of longest uninterrupted sequence of capital letters
-	1 continuous integer [1,...] attribute of type capital_run_length_total = sum of length of uninterrupted sequences of capital letters = total number of capital letters in the e-mail
-	1 nominal {0,1} class attribute of type spam = denotes whether the e-mail was considered spam (1) or not (0), i.e. unsolicited commercial e-mail.
Classification distribution:
-	Spam		1813 (39.4%)
-	Non-spam	2788 (60.6%)

2. Machine learning models for spam email data classification
Machine learning models are applied including:
-	Logistic regression
-	Neural network
-	Support Vector Machine
-	Random forest
-	Convolutional deep neural network
All machine learning models are supervised learning. The inputs are features listed above. The output is spam or non-spam.
The machine learning models are realized by using Jupyter Notebook based on Python3. The canonical models consist of Logistic regression, Neural network, Support Vector Machine and committee model Random forest use Sklearn package. In addition, CNN uses Tensorflow which extends Sklearn package for training.

