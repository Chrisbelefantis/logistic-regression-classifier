# Overview
Using **BanckChurners** dataset which holds the data of about **10,000 clients** we want to predict which of them are possible
to unsubscribe from the banks services in order to active special offers for them. The main difficulty in this dataset is that 
about the 85% percent of the samples are clients who didn't unsubscribe from the banks services *( y = 0 )*, so the dataset is 
skewed.

In order to train a model in those circumnstances we used the below techniques:
* Model evaluation using **precision**, **recall** and **f-score**
* Oversampling
* Recursive Feature Elimination
* Polynomial Features

