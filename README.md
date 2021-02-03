# AI-Chatbot-with-Tensorflow
This is a Chatbot which i created for my final year engineering project. It is fully written in python and for training and modelling i have used Tensorflow. finally GUI is created with Tkinter in python my goal was to make this project more real world. Chatbot can be integrated with web too, Using flask nd tensorflow serving, but i haven't done that yet. 

# Working  
So, the flow of the chatbot is as follows:
  1. First we have a file called 'intents.json', in this file we have a set of predefined questions and answers. All questions and answers can be seperated by 'tags'. 'tags' here means a specific topic or category of a question. For ex, tag=Canteen means the question asked by the user falls into canteen category.  
  2. You can easily add or delete questions/answers into/from the intents.json file.  
  3. We have a neural network which will train on the questions, obviously we need to convert text into bag-of-words representation in order to do that. Here, we will learn the association between the question and the tag. Which means our feature variable is Bag of words representation of the questions and our target varaible is the tag associated with those questions. Yes, it's a classification task.
  4. Once we find the tag, we just need to return an answer for that tag entry through the json file.
  


## Watch the demo here:  
[![Demo for PVPP Assistant](https://img.youtube.com/vi/duDOyhrlYYw/0.jpg)](http://www.youtube.com/watch?v=duDOyhrlYYw "PVPPCOE Assistant")

