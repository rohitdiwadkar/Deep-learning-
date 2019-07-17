# Deep-learning- Classification on the accessibilty of product if the product is subscribed or not.

This assignment is about classification of labels using deep learning. In Deep learning we use lots of python library for the above objective , for example : tensorflow or keras.

I used keras for implementation of deep learning on bank marketing data. In this we used sequential model of keras.

Data Visualization -- Classification
So for Classification I chose " Bank Marketing data" dataset from UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/bank+marketing). The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

There are 17 variables and in total 45211 records . The folowing are the attribute Information:

Input variables:

1 - age (numeric)

2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')

5 - default: has credit in default? (categorical: 'no','yes','unknown')

6 - housing: has housing loan? (categorical: 'no','yes','unknown')

7 - loan: has personal loan? (categorical: 'no','yes','unknown')

8 - contact: contact communication type (categorical: 'cellular','telephone')

9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

10 - day: last contact day.

11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no').

12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

14 - previous: number of contacts performed before this campaign and for this client (numeric)

15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

16 - y : has the client subscribed a term deposit? (binary: 'yes','no')

17 - Balance : balance in the bank account (numeric)


We build a deep learning model using Keras and used cross validation for splitting the train and test data for good fit and performance.

I tried different number of hidden layers for good structure of nodes and good accuracy.

Choice of Network Structure
So if we go through the above scenarios, we can see that if we change the number of layer in the network structure , the classification and accuracy changes accordingly. Less and precise number of neurons and layers can yield you good results. Pruning also describes a set of techniques to trim network (by nodes not layers) to improve computational performance. The gist of these techniques is removing nodes from the network during training by identifying those nodes which if removed from the network, would not noticeably affect network performance.

Conclusion:

Deep Learning is very important part of machine learning and artificial intelligence which specially used in software agents and machines are made to ascertain the ideal output in a specific deep network with the aim of maximizing its performance.

From this assignments I learned alot and faced lot of challenges:

The number of network confused alot to which there was some errors arised while designing the model and the data given as input.

It was very difficult to set the epochs which made difficult to calculate the accuracy and plot it.

I learned alot about Deep learning through this assignment and about correct network structure selection by experimenting or pruning.

Also learned about the tensorflow and keras.

