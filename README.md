# Chatbot Product
## Background
A Travel company wants to create a chat product that allows users to query flight prices, hotels and car rentals through conversation.

## Objective
To create a POC model that is able to extract locations (to and from), dates and prices ranges from conversational text.

## Data Sources
Data used for the project was mainly sourced from Travel websites

## Methodology
* Data was unpacked in a json file as different groups of intent, tags, patterns and responses
* Data was preprocessed using;
	* Stemming
	* Lemmatizing
	* Tokenizing, and 
	* Bag of words
* Trained data, derived from the bag of words, was fed into Deep Neural Network (DNN) using tflearn
* Response predictions were made based on input patterns from a user

## How it Works
* User interacts with the bot via a prompt
* User enters input requests in line with patterns the model has been trained with
* The model, via the bot, outputs a response that corresponds to the response with highest predicted probability
