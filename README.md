# Deep Learning based Chatbot App
The project contains a flask app that uses a deep learning model to chat with a real time user. The app uses a keras to create and train the predicting model which learns from a pre made dataset.

The dataset is stored in a json file which has the list of "intents" based on which samples are taken from the data to train the model to provide accurate response.

The predicting model is created using sequential model of Keras and NLTK is used for processing the words, which essentially means going through the intent file and tokenizing it so that the model can work with it.

Jquery and Ajax are used in the flask app to enable communication with the user and send back the predictedd response.

## Screenshots
Here is how the frontend looks.

![Screenshot-Output](Frontend.png?raw=true "Title")
