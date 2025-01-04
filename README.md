# Serverless-Banking-ChatBot
## Objective:
This project demonstrates how to build and connect an Amazon Lex chatbot with AWS Lambda to create a serverless application for checking bank account balances. The goal is to integrate a conversational interface with a backend compute service to deliver a seamless user experience.

## What is Amazon Lex?
Amazon Lex is a service for building conversational interfaces like chatbots and voice assistants. It leverages **Natural Language Understanding (NLU)** and **Automatic Speech Recognition (ASR)** to interpret user input and respond appropriately.

### Use of Amazon Lex in This Project:
- Created a chatbot named **BankerBot** with the intent to check the user's bank balance.
- Utilized **TestBotAlias** to manage versions of the chatbot and connect with the AWS Lambda function.

## AWS Lambda Functions:
- AWS Lambda is a serverless compute service that automatically manages infrastructure while executing code in response to events.
- A Lambda function titled **BankingBotEnglish** was created to process the user requests received from the chatbot.
- This function was written in Python and integrated with the chatbot via aliases and **code hooks** for enhanced functionality.

## Code Hooks:
- Code hooks enable Lambda functions to process user input and provide dynamic responses.
- Used in this project to extend the chatbot’s capabilities and connect it with backend services.

## Chatbot Alias:
- The alias **TestBotAlias** was utilized to point to a specific version of the chatbot and facilitate seamless integration with the Lambda function.

## Final Result:
The Amazon Lex chatbot, **BankerBot**, triggers the Lambda function **BankingBotEnglish** to return the user's bank balance when prompted. This architecture ensures a robust and scalable interaction between the chatbot and the backend.

## Key Achievements:
- Successfully designed and deployed a conversational interface using Amazon Lex.
- Integrated Lambda functions to enable serverless processing of user requests.
- Leveraged AWS tools to build a scalable and efficient serverless application.

## Challenges:
- Navigating the implementation of serverless infrastructure with Amazon Lex for the first time.
- Understanding and configuring aliases, code hooks, and Lambda connections.

## Timeline:
This project was built in **1 hour**, with most of the time spent configuring Amazon Lex, as this was the first experience with AWS ML services.


---

### Author:
David Osaik  
**Contact:** david.osaik@yahoo.co.uk  
