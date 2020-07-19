# Sparkify
Sparkify Project for Data Scientist
Sparkify project
Table of Contents
Installation
Project Motivation
Files Description
Result
Licensing, Authors, and Acknowledgements
Installation 
This project uses the following software and Python libraries:
Python 3.6
Spark
Pyspark 3.0
pandas 0.19
Matplotlib
Seaborn
You will also need to have software installed to run and execute a Jupyter Notebook.
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. And for Spark, you can do this using AWS or IBM Cloud.
Project Motivation
This is udacity's capstone project, using spark to analyze user behavior data from music app Sparkify.
Sparkify is a music app, this dataset contains two months of sparkify user behavior log. The log contains some basic information about the user as well as information about a single action. A user can contain many entries. In the data, a part of the user is churned, through the cancellation of the account behavior can be distinguished.
Files Description
Sprakify .ipynb Main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.
Result
The best model is logistic regression. According to the results of the model, Registration time has the greatest impact.,the longer the registration time users will not leave.
Besides, the frequency of downgrade pages is also a big factor. I think this is because users hate the downgrade prompt. 

Licensing, Authors, Acknowledgements
Must give credit to Udacity for the project. You can't use this for you Udacity capstone project. Otherwise, feel free to use the code here as you would like!
