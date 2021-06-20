# Python-University-Chatbot
In this project, a university chatbot has been developed (on python 3.6) specifically for the University of Wollongong in Dubai (UOWD). The chatbot can aid students who are interested in joining UOWD, as well as current UOWD students. The chatbot can offer support by suggesting appropriate majors/programs based on grades and interests; answering general university related questions; informing students on exam and event schedules. The algorithm is based on a simple feed-forward neural network with two fully connected hidden layers and a fully connected Softmax layer. The framework first has conversational intents defined (with a JSON file) and then transformed to a Tensorflow model. 

***Details for setting up the chatbot***

•	You must use an environment with Python 3.6

•	You must have both the python and JSON files in the same directory before you run the code. 
To change the command prompt directory to a specific location:
CD name\name\name or just CD name (for one file change)

•	The required libraries are given below along with the commands to install them in your Python 3.6 environment.
Libraries
nltk -> python -m nltk.downloader all  (you can also use nltk.download(‘punkt’) 
numpy -> pip install hdf5
tflearn -> pip install tflearn
tensorflow -> pip install tensorflow
curses -> pip install windows-curses
hdf5 -> pip install hdf5
Scipy -> pip install Scipy

Once the setup is complete, simply open the command prompt, activate the environment, move directory to location of code files, then type: python main2.py in the command prompt to run the code.

