# IBM_HACKATHON

# Real-Estate-House-Price-Predictor
This repository includes an open source project which combines Data Science, Microservices and Artificial Intelligence. The aim of this project is to demonstrate data science outcomes inside a chatbot. We analyze a real estate property dataset and construct a model. Then we predict the approximate prices of new properties. We display them via chatbot.


# Create an assistant that predicts real estate prices 

Deploy an app in Kubernetes that communicate with your data science workbench and demonstrate your findings in a customized chatbot 


## [Get the code](https://github.com/Aditya-Karmalkar/IBM_HACKATHON)


## Summary
In this code pattern, we will create an assistant that estimates real estate prices with a data science platform in the background and under the control of a containerized application in Kubernetes. The user will provide the features of a house that he or she wants and the result is calculated and displayed to user immediately. In this way, users can quickly obtain the price information of the house that they are seeking for without any research.

## Technologies

All your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.

 - Artificial Intelligence

- Containers

- Conversation

- Data Science

- Machine Learning

- Microservices

- Object Storage

- Python

## Description

Sometimes while applying Data Science into our everyday applications, we have insufficient resources to demonstrate our work. For example, when we want to share our research findings with our teammates in workplace, we may not have our laptop with us at that moment, or we may not access slides that contains our results with good visuals. Therefore, we may not be able to impress our colleagues and we feel frustrated. However, we forget the fact that we always have our mobile phones with ourselves and they can be the perfect tool for displaying our efforts in anywhere at any time. In this pattern, we will walk through how to show our hard work easily with IBM Watson Assistant, Watson Studio, Node-RED, Kubernetes Service and machine learning libraries such as pandas and scikit-learn.

This pattern is based on the dataset of House Sales in King County  which includes Seattle, USA. It includes homes sold between May 2014 and May 2015. The reason behind choosing this dataset is that when we want to search for a new house for ourselves, we need to go to real estate agencies and the process of visiting each one of them require lots of effort and we may want to have a quick look at the approximate prices for our desired house.

After going through this pattern, you will be able to:

- Use Watson Studio

- Prepare a dataset from scratch with machine learning libraries

- Visualize your data

- Use IBM Watson Machine Learning Model Builder Service

- Understand and implement WebSocket communication protocol

- Deploy a Node-RED application in IBM Kubernetes Service

- Use Watson Assistant and integrate it into a Telegram Bot

This pattern is created for data science enthusiasts who seeks for different ways of delivering and displaying results with ease. This pattern does not guarantee that the price will be exactly the same as predicted in the pattern but close to the real price offered by real estate agencies.

## Flow
1. Open Watson Studio and create a notebook.

2. Download the dataset into Watson Studio and prepare it for modeling.

3. Export the prepared dataset and give it to IBM Machine Learning Model Builder Service (create one) for choosing the regression algorithm.

4. Implement the regression algorithm in Watson Studio and calculate the accuracy.

5. Implement WebSocket client inside Watson Studio.

6. Create a cluster from IBM Kubernetes Service and install Node-RED service into it.

7. Create a Watson Assistant.

8. Create a Telegram Bot.

9. Create a Node-RED flow that connects Watson Assistant to Telegram Bot.

10. Add nodes to current Node-RED flow that implements WebSocket communication (both server and client) and connects Watson Assistant to Telegram Bot.

11. Calculate and display the estimated price in Telegram bot based on house features given by user.


## Instructions
Find the detailed steps for this pattern in the README. This code pattern consists of three primary activities:
1. Run a Jupyter notebook in Watson Studio and use Watson Machine Learning.

2. Create IBM Kubernetes Service cluster and install Node-RED into it.

3. Create a Watson Assistant Chatbot and connect it to Telegram via Node-RED. Add necessary flows to Node-RED.
