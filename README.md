# CA02: Gauss Naive Bayes Model: Spam eMail Detection using Naive Bayes Classification Algorithm


![how to stop spam emails](https://www.hellotech.com/blog/wp-content/uploads/2020/03/how-to-stop-spam-emails-768x461.jpg)
# Spam eMail Filter Project Description

In this exercise we shall train the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. Next, we shall test the model on 260 emails. We shall ask model to predict the category of this emails and compare the accuracy with correct classification that we already know.

# Dataset

The data set can be downloaded via github: 
("https://github.com/ArinB/MSBA-CA01-Spam-Mail-Naibe-Bayes")
Or via google drive:
("https://drive.google.com/drive/u/0/folders/1PvLaOPHQ7m50NZFwUeQfwq1c")

Upon downloading the dataset, we created python notebook for our further 
analysis.
# Code

Python Notebook: 
("https://github.com/dhimansarkar18/CA02-Spam-eMail-Detection-using-Naive-Bayes-Classification-Algorithm/blob/main/CA_02_Dhiman_Sarkar.ipynb")
Google Colab: ("https://colab.research.google.com/drive/1YLNwSZtmy9JlnrdDnoDwziMLlQDDcIbZ#scrollTo=134lmhauyQxE")

# Instructions on how to launch
I. Open the python notebook on google colab.
II.  Mount the Google Drive: drive.mount("/content/drive")
III.  Link the working directories: 
test = "/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA02/Data/test-mails"

train = "/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA02/Data/train-mails"
IV. Run the Code
V. The last section in the code displays the accuracy score

# Procedures

In order to create our model we followed the following steps:
I. Acquiring/Downloading the Dataset
II. Uploading/Ingestion of the Dataset into Google Drive
III. Mounting the drive to our google colab python notebook
IV. Importing the Necessary Packages (os,numpy,Counter,GaussianNB,accuracy_score)
V. Reading the Dataset
VI. # Defining a function with 3000 most common words from all emails
VII. # Defining a function which extracts feature columns and populates their values
VIII. Calculating accuracy scores for predicting labels
IX. Observations and Findings by studying the output

# Author

This study was conducted by Dhiman Sarkar, MS. Business Analytics 21' - Loyola Marymount University.
("https://github.com/dhimansarkar18")
