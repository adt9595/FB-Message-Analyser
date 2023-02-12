# FB-Message-Analyser
Tool for extracting interesting information from FB messenger chats and group chats

NOTE: When you download your data from FB, you will only obtain messages from a group chat that were posted after you had joined that chat, so if you want a comprehensive representation of the data in that group chat, and original member of the chat should be doing the analysis

## Key Features
* Find the most used words in the history of your chat
* Find how many messages each member of the chat has posted

## Setup
* Download the script
* To use this on your FB message data, you'll first need to download your data from FB **in JSON format**. Note that this script only works with JSON formatted data. The steps for how to do this [can be found here](https://www.facebook.com/help/212802592074644)
* Once you have downloaded and extracted the zip of your data, find the folder of your chat that contains a list of JSON files formatted message_1, message_2 etc..., and place the script in this folder
* Open the script in your very favourite Python environment

## Usage
* At the bottom of the file, there will be the line
```
analyser = ChatAnalyser()
```
This is the instance of the chat analyser from which you can get all kinds of exciting information
