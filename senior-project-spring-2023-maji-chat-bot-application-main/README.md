Maji Chatbot Senior Project - README

Vivek K. Maheshwari
Kaung Min Sett


Project Description
The AI Chatbot Senior Project is an application that uses natural language processing and machine learning techniques to understand and respond to user inputs in a conversational manner. 
This chatbot has been designed to be capable of holding an extended conversation and answering a wide range of questions on various topics. 
The project was inspired by the chatbot ChatGPT.

Goals and Objectives
The primary goal of the Maji AI Chatbot is to create an AI chatbot that can carry out human-like conversations and answer a wide range of questions on various topics. 
The objectives of the project include:
-Building a dataset of conversational data for the chatbot to learn from
-Implementing natural language processing techniques to understand user input
-Developing a machine learning model to train the chatbot on the dataset
-Integrating the trained model with a chatbot interface to enable users to converse with the chatbot
-Testing and evaluating the chatbot's performance on a variety of questions and conversation scenarios

Requirements
To run the Maji AI Chatbot, you will need the following:

Python 3.7 or higher
pip3 package manager
NLTK (Natural Language Toolkit) 3.5 or higher
Pytorch version 2.0.0 is used for the implementation
Torchtext 0.3.0 is used for loading the Squad dataset

Installation
Clone the repository to your local machine using the following command: git clone https://github.com/<username>/senior-project-spring-2023-maji-chat-bot-application.git.
Install the required packages using pip3: pip3 install -r requirements.txt.
Download the NLTK data by opening a Python shell and typing:

import nltk
nltk.download()

This will open a GUI that allows you to download the required data. 
Alternatively, you can download the data directly using the following command: 
python3 -m nltk.downloader all.

Usage
To run the AI Chatbot Senior Project, navigate to the root directory of the project and run the following command: 
python3 chatbot.py.

This will start the chatbot application, and you can begin conversing with it by typing messages into the console. 
The chatbot will respond with a text message that you can read and respond to accordingly. 
To exit the chatbot application, simply type "exit" into the console.

Training
If you want to train the Maji AI Chatbot on your own dataset, you can use the train.py script. 
The script takes the following arguments:
--data_dir: Path to the directory containing the training data.
--model_dir: Path to the directory where the trained model will be saved.
--num_epochs: Number of epochs to train the model for (default: 100).
--batch_size: Batch size to use during training (default: 64).
--learning_rate: Learning rate to use during training (default: 0.001).

To run the training script, navigate to the root directory of the project and run the following command: 
python3 train.py --data_dir /path/to/training/data --model_dir /path/to/model/directory.

Risks and Mitigation
The following risks have been identified for the Maji AI Chatbot:

The chatbot may not be able to provide accurate and informative responses: 
We will mitigate this risk by extensively testing and refining the chatbot's performance.
The dataset may be insufficient for the chatbot to learn from: 
We will mitigate this risk by collecting and cleaning a large and diverse dataset.
Technical issues may arise during development: 
We will mitigate this risk by ensuring that all team members are skilled in the required technologies and by having a contingency plan in place in case of technical issues.

Conclusion
The Maji AI Chatbot is an ambitious project that will require significant effort and skill to complete.

Contributing
If you would like to contribute to the Maji AI Chatbot, please submit a pull request on GitHub.
We welcome contributions of all kinds, including bug fixes, new features, and documentation improvements.

License
The Maji AI Chatbot Senior Project is licensed under the MIT License. See the LICENSE file for more information.
