# Chatbot
Developed the student chatbot application using NLP, Cosine similarity and Python Flask.
Required package installations:
Numpy
NLTK 
Sklearn
Software requirements:
1. PyCharm
2. Python
# data.csv:
Contains two columns query and response
# chatf.py:
-Preprocessed the data
-Computed the maximum similarity using TFIDF and cosine similarity
# chat.py
- Imported class from chatf.py and the method get_response is called
# chatapp.py
- The root route (/): displays the chat interface to the user by rendering the index.html template.
- /ask route, on the other hand, is designed to manage incoming POST requests. It anticipates JSON data containing a messageText field. This route processes the user's input using the chatbot function and sends back the chatbot's response in JSON format.
# index.html
- Chatbot interface



