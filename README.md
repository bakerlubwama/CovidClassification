In this project I compare the performance of the KNNs (K-nearest neighbors) algorithm with that of a simple neural network on a binary classification of death/recovery from COVID-19.

Classification is based off of patient data points such as age, gender, symptoms, geographic data etc.
The dataset was provided through the University but I believe it is also publicly available.

Note that all the data within the dataset is numerical. This is because in the preprocessing, all the categorical data was label-encoded into numerical data as this is what machine learning models work with. 

Most of the code will be found within the 'covid_classification.ipynb' file within the 'notebooks' folder. 

The basis and idea for this project came from this paper: https://www.frontiersin.org/articles/10.3389/fpubh.2020.00357/full
