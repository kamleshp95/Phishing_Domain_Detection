# Phishing Website Detection by Machine Learning Techniques iNeuron Internship

## Objective
A phishing website is a common social engineering method that mimics trustful uniform resource locators (URLs) and webpages. The objective of this project is to train machine learning models and deep neural nets on the dataset created to predict phishing websites. Both phishing and benign URLs of websites are gathered to form a dataset and from them required URL and website content-based features are extracted. The performance level of each model is measures and compared.

## Dataset
*Dataset Link : [Dataset](https://data.mendeley.com/datasets/72ptz43s9v/1)*
## Models & Training

Before stating the ML model training, the data is split into 80-20 i.e., 8000 training samples & 2000 testing samples. From the dataset, it is clear that this is a supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression.

This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are:

* Decision Tree
* Random Forest
* Multilayer Perceptrons
* XGBoost
* Autoencoder Neural Network
* Support Vector Machines

All these models are trained on the dataset and evaluation of the model is done with the test dataset. 

## End Results
From the obtained results of the above models, XGBoost Classifier has highest model performance of 96.6%. So the model is saved to the file 


## For Running the project in local machine 

Run app.py present in " Hosting Folder "

### Project Demo Video [link](https://youtu.be/dCRaaellqLc)


