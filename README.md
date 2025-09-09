# Fake_News_Detector
Utilizing Bidirectional LSTM model with DistilBERT word embeddings to classify news as fake or real

*This project is a group work with Oğulcan Karakollukçu*

To execute the entire project in Google Colab, follow these steps:

Step 1: Prepare the Required Files and Keys
Kaggle API Key (kaggle.json):

Obtain your Kaggle API key:
Log in to your Kaggle account.
Go to "My Account" from the profile dropdown.
Scroll to the "API" section and click "Create New API Token."
Download the kaggle.json file.
This file is required to access datasets hosted on Kaggle. You will upload it to Colab in Upload the Kaggle Dataset part.

Step 2: Hugging Face API Key:
Create a Hugging Face account at Hugging Face.
Go to "Settings" > "Access Tokens" and create a new token with appropriate permissions.
Copy the token for use in the notebook_login function.


Step 3: Weights and Biases (wandb) API Key:
Sign up at Weights and Biases and log in.
Go to your account settings to retrieve your API key.
This is used to track training metrics during DistilBERT model training.

Info:
This ipynb file can be executed in nearly 40 minutes with A100 GPU in Google Colab.
Datasets are loaded to the program with commands. The user must enter the correct keys.
To skip the baseline DistilBERT model training and testing part, the user must command all the code between the markdowns COMMAND 1 and COMMAND 2.

Recommended executing:
Command all the code between the markdowns COMMAND 1 and COMMAND 2.
Prepare reqired API Keys.
Open the ipynb in Google Colab and connect to A100 GPU.
Click "execute all" and when it is time enter the API keys.
