# Chatbot

This is the last project I have built in the **Natural Language Processing with Attention Models** course on Coursera.

This readme is taken exactly from the project description in the Notebook itself.

<img src = "cbot.jpg" height="400" width="400"> 

In this assignment, you are going to use the [Reformer](https://arxiv.org/abs/2001.04451), also known as the efficient Transformer, to generate a dialogue between two bots. You will feed conversations to your model and it will learn how to understand the context of each one. Not only will it learn how to answer questions but it will also know how to ask questions if it needs more info. For example, after a customer asks for a train ticket, the chatbot can ask what time the said customer wants to leave. You can use this concept to automate call centers, hotel receptions, personal trainers, or any type of customer service. By completing this assignment, you will:

* Understand how the Reformer works
* Explore the [MultiWoz](https://arxiv.org/abs/1810.00278) dataset
* Process the data to feed it into the model
* Train your model
* Generate a dialogue by feeding a question to the model


## Outline
- Part 1:   Exploring the MultiWoz dataset
	- Exercise 01
- Part 2:   Processing the data for Reformer inputs
    - 2.1   Tokenizing, batching with bucketing
- Part 3:   Reversible layers
	- Exercise 02
	- Exercise 03
    - 3.1   Reversible layers and randomness
- Part 4:   ReformerLM Training
	- Exercise 04
	- Exercise 05
- Part 5:   Decode from a pretrained model
	- Exercise 06
