---
layout: post
title: Understanding Machine Learning
date: 2020-11-28 00:00:00 +0300
description: 
img: machine-learning.jpg
tags: [Data Analysis, Data Analyst, Data Driven, Big Data, Business Intelligence, Machine Learning, Decision Optimization]
---

Machine learning is used all around us - in our work and personal lives - without many of us realizing that our daily tasks are being used to train algorithms that do everthing from increase our work efficiency to determine our buying patterns. It can be used to predict SEO rankings. It is used by social media platforms to predict user behavior. Amazon uses it for product promotion. And Google uses it for advertising optimization. Smart home devices, digital assistants, website recommendations based on previous web activity, spam filters for emails, robot vacuums, self driving cars and more are all examples of machine learning.

And we can expect even more. As big data keeps getting bigger, computing becomes more powerful and affordable, and as we keep developing more capable algorithms, machine learning will drive greater results and efficiency in our personal and work lives. 

So, what exactly is it and how does it work?

# What is Machine Learning?

Machine Learning is a powerful (AI) technology that extracts information from historical data to give you insights like predictive customer behaviors and business forecasts without specifically being programmed to do so. Over time, the machine learning algorithm improves its accuracy as it continuously learns from the data set.

In data science, an algorithm is a sequence of statistical processing steps. In machine learning, algorithms are 'trained' to find patterns and features in massive amounts of data in order to make decisions and predictions based on new data. The better the algorithm, the more accurate the decisions and predictions will become as it processes more data.

# How Machine Learning Works

The idea behind machine learning is to create a system that answers a particular question. This question answering system is called a *model* and it is created via a process called *training*. The main goal of training is to create an accurate model that answers our questions correctly, at least for most of the time. But in order to train a model, you need to collect data on what you want to train on. A machine learning workflow looks something like this:

* Gathering data
* Preparing the data
* Choosing an algorithm
* Training
* Evaluation

Let's look at these in more detail.

# Gathering and Preparing Data
Gathering data is a crucial step as the quality and quantity of data gathered will directly determine how good the predictive model will turn out to be. After the data is gathered, you move on to the next step which is data preparation. This step is where the data is loaded into a suitable place and then prepared for use in training. The training data needs to be properly prepared by randomizing it, de-duping, and checking for imbalances or biases that could impact the training. It should also be divided into two subsets: the *training subset*, which will be used to train the application, and the *evaluation subset*, used to test and refine it.

# Choosing an Algorithm
An algorithm is a set of statistical processing steps. The type of algorithm depends on the type (labeled or unlabeled) and amount of data in the training data set and on the type of problem to be solved. Common types of machine learning algorithms include:
* Regression algorithms
* Decision trees
* Instance-based algorithms
* Clustering algorithms
* Association algorithms
* Neural networks

# Training 
This step is considered the bulk of machine learning, called *training*, where the data is used to incrementally improve the model’s ability to predict. The training process involves initializing random values for our model, predicting the output with those values, then compares it with the model's prediction and adjusts the values so that they match the predictions that were made previously.

This process repeats until the algorithm returns the correct result most of the time. The resulting *trained*, accurate algorithm is the machine learning model — an important distinction to note, because 'algorithm' and 'model' are incorrectly used interchangeably.

# Evaluation 
Using the *evaluation subset* mentioned earlier, this step tests the model against data that has never been seen and used for training, and is meant to be representative of how the model might perform when in the real world.
