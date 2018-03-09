# Social
A project made for MIT Blueprint Feb 18. 2018
Ever find yourself struggling to make conversation? Want to improve your sense of humor? Well, then get SOCIAL!

Social is an app that integrates into messaging services that automatically analyzes messages and suggests relevant jokes or topics to talk about, with added sentiment analysis to let you know how well the conversation is going!

# How it works
With a database of jokes scraped off of websites like reddit, stupidstuff, and wocka, a distilled (shorter/cleaner) joke database is parsed and sorted by keywords. Incoming user messages are parsed into keywords using a tokenizer and are quickly matched with relevant jokes in the database to be suggested.

For the sentiment analysis, Machine Learning models were made in order to classify textdata into emotions.

The app is then launched on a chatroom built on Python's own built-in socket with a GUI using Tkinter. (In the future, optimally this app would be able to be integrated into any messaging service like facebook messenger, skype, or slack).

For more information and inspiration behind the app, see https://devpost.com/software/social-hmzeaf
