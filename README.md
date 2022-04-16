# Climate-Change-Classification

## Description
Many companies are built around lessening one’s environmental impact or carbon footprint. They offer products and services that are environmentally friendly and sustainable, in line with their values and ideals. They would like to determine how people perceive climate change and whether or not they believe it is a real threat. This would add to their market research efforts in gauging how their product/service may be received.

With this context, as a team of five we took up the challenge of creating a Machine Learning model that is able to classify whether or not a person believes in climate change, based on their novel tweet data.

This was done with the aim of providing an accurate and robust solution that would grant companies access to a broad base of consumer sentiments, spanning multiple demographic and geographic categories - thus increasing their insights and informing future marketing strategies.

## Attached files
Attached within this repository is the Main folder containing the streamlit app save as 'base_app.py' and the resources folder. The resources folder contains dependencies needed for the streamlit app to run and also the Jupyter Notebook used while interacting with the data and model building.

## Models
Five models were built, Support Vector Classifier, Multinomial Naive-Bayes, Logistic Regression, K-Nearest Neighbours and Random Forest classifier models. 
Of the five Logistic regression model perfomed best while the Random Forest Classifier perfomed worst in termss of F1-Score.
Each of the five models are saved as pickle files in the resources folder and can be tested with the local streamlit app.

## Model Deployment
The models were deployed on the streamlit app and run on an AWS EC2 instance. To check the perfomance of the different models from the streamlit app, Install  the streamlit app locally from your terminal using 'pip install streamlit'.
Clone the repository in your machine and from your terminal change directory into the folder you just cloned the repository into the run the command 'streamlit run base_app.py' click enter and you'll be able to interact with the models locall from the comfort of your default browser!
